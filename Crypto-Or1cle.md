# Crypto-Or1cle

```python
23: self.P = self.d*secp256k1.G
24:
25: def signature(self,msg):
26: h = int(hashlib.sha256(msg).hexdigest(),16)
27: k = h^self.d
28: r = (k*secp256k1.G).x
29: s = inverse(k,secp256k1.q) * (h + r*self.d) % secp256k1.q
30: return '%064x%064x' % (r, s)
31:
32: def verify(self,z, signature):
33: r, s = int(signature[:64], 16), int(signature[64:], 16)
34: z = int(hashlib.sha256(z).hexdigest(), 16)
35: s_inv = pow(s, secp256k1.q - 2, secp256k1.q)
36: u1 = (z * s_inv) % secp256k1.q
37: u2 = (r * s_inv) % secp256k1.q
38: point = u1 * secp256k1.G + u2 * self.P
39: return point.x == r
40:
41: banner = """
42: _  __                                       __________        ___________
43: | |/_/__ ___  ___  __ __    __              /\____;;___\      |          |
```

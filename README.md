# Injection layer, i from Euclidean space to Hyperbolic space

```
injection i:
x = <x1, x2 .. xN> in Euclidean space
->
u = i(x) = <x1, x2 .. xN> in Hyperbolic space
    where
        Sum_i x[i]^2 < 1
```

## the distance in Hyperbolic space

```
d(u, v) = arccosh[ 2 * d_E(x, y)^2 / (1 - d_E(0, x)^2) / (1 - d_E(0, y)^2) + 1]
    where
      u = i(x)
      v = i(y)
      d_E(x, y) = |x - y|  -- the distance in Euclidean
      arccosh(z) = log[ z + sqrt(z - 1) * sqrt(z + 1) ]
```

## Riemannian metric

```
g(x) = ( 2 / (1 - d_E(0, x)) )^2 * g^E
    where
      g^E is the Euclidean metric (i.e. E)
```

# Injection layer from Euclidean space to Hyperbolic space

```
injection:
x = <x1, x2 .. xN> in Euclidean space
->
u = <x1, x2 .. xN> (= i(x)) in Hyperbolic space
    where
        -1 < x[i] < 1
```

## the distance in Hyperbolic space

```
d_E(x, y) = |x - y|  -- the distance in Euclidean
d(u, v) = arccosh[ 2 * d_E(x, y)^2 / (1 - d_E(0, x)^2) / (1 - d_E(0, y)^2) + 1]
    where
      u = i(x)
      v = i(y)
      arccosh(z) = log[ z + sqrt(z - 1) * sqrt(z + 1) ]
```

## Riemannian metric

```
g(x) = ( 2 / (1 - d_E(0, x)) )^2 * g^E
  where
    g^E is the Euclidean metric (i.e. E)
```

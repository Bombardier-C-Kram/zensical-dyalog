---
search:
  boost: 2
---
<div style="display: none;">
  , ravel
</div>

# Ravel

```apl
R←,Y
```

`Y` may be any array.  `R` is a vector of the elements of `Y` taken in row-major order.

## Examples
```apl
      M
1 2 3
4 5 6
 
      ,M
1 2 3 4 5 6
 
      A
ABC
DEF
GHI
JKL
      ,A
ABCDEFGHIJKL
 
      ⍴,10
1
```

See also: [Ravel with Axes](ravel-with-axes.md).




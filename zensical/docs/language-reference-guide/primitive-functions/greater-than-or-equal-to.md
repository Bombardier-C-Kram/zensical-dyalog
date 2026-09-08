---
search:
  boost: 2
---
<div style="display: none;">
  ≥ greater
</div>






# Greater Than Or Equal To

```apl
R←X≥Y
```



`Y` must be numeric. `X` must be numeric. `R` is Boolean. `R` is 1 if `X` is greater than `Y` or `X=Y`. Otherwise `R` is 0.


`⎕CT` and `⎕DCT` are  implicit arguments of Greater Than Or Equal To.

## Examples
```apl
      1 2 3 4 5 ≥ 3
0 0 1 1 1
 
      ⎕CT←1E¯10
 
      1≥1
1
 
      1≥1.00000000001
1
 
      1≥1.00000001
0
```




---
search:
  boost: 2
---
<div style="display: none;">
  ⍱ nor
</div>






# NOR

```apl
R←X⍱Y
```



`Y` must be a Boolean array. `X` must be a Boolean array. `R` is Boolean. The value of `R` is the truth value of the proposition "neither `X` nor `Y`", and is determined as follows:
```apl
             X   Y     R
      
             0   0     1
             0   1     0
             1   0     0
             1   1     0
```

## Example
```apl
      0 0 1 1 ⍱ 0 1 0 1
1 0 0 0
```




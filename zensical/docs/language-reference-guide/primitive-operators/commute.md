---
search:
  boost: 2
---
<div style="display: none;">
  ⍨
  commute
</div>






# Commute

```apl
{R}←{X}f⍨Y
```



`f` may be any dyadic function.  `X` and `Y` may be any arrays whose items are appropriate to function `f`.


The derived function is equivalent to `YfX`.  The derived function need not return a result.


If left argument `X` is omitted, the right argument `Y` is duplicated in its place, that is:
```apl
      f⍨Y ←→ Y f⍨Y
```


## Examples
```apl
      N
3 2 5 4 6 1 3
 
      N/⍨2|N
3 5 1 3

      ⍴⍨3
3 3 3


      mean←+/∘(÷∘⍴⍨) ⍝ mean of a vector
      mean ⍳10
5.5
```


The following statements are equivalent:
```apl
      F/⍨←I
      F←F/⍨I
      F←I/F
```


Commute often eliminates the need for parentheses



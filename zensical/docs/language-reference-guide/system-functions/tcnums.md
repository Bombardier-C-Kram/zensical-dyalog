---
search:
  boost: 2
---
<!-- Hidden search keywords -->
<div style="display: none;">
  ⎕TCNUMS TCNUMS
</div>






# Thread Child Numbers

```apl
R←⎕TCNUMS Y
```



`Y` must be a simple array of integers representing thread numbers.


The result `R` is a simple integer vector of the child threads of each thread of `Y`.

## Examples
```apl
      ⎕TCNUMS 0
2 3
 
      ⎕TCNUMS 2 3
4 5 6 7 8 9
```




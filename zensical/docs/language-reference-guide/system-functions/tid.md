---
search:
  boost: 2
---
<!-- Hidden search keywords -->
<div style="display: none;">
  ⎕TID TID
</div>






# Current Thread Identity

```apl
R←⎕TID
```



`R` is a simple integer scalar whose value is the number of the current thread.

## Examples
```apl
      ⎕TID     ⍝ Base thread number
0
 
      ⍎&'⎕TID' ⍝ Thread number of async ⍎.
1
```




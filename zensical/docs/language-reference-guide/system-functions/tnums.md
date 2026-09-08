---
search:
  boost: 2
---
<!-- Hidden search keywords -->
<div style="display: none;">
  ⎕TNUMS TNUMS
</div>






# Thread Numbers

```apl
R←⎕TNUMS
```



`⎕TNUMS` reports the numbers of all current threads.


`R` is a simple integer vector of the base thread and all its living descendants.

## Example
```apl
      ⎕TNUMS
0 2 4 5 6 3 7 8 9
```




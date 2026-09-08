---
search:
  boost: 2
---
<!-- Hidden search keywords -->
<div style="display: none;">
  ⎕NNUMS NNUMS
</div>






# Native File Numbers

```apl
R←⎕NNUMS
```



This niladic function reports the tie numbers associated with all currently open native files.  `R` is an integer vector of negative tie numbers. The elements of the result are in the order in which the files were tied.




---
search:
  boost: 2
---
<!-- Hidden search keywords -->
<div style="display: none;">
  ⎕XT XT
</div>






# Query External Variable

```apl
R←⎕XT Y
```



`Y` must be a simple character scalar or vector which is taken to be a variable name.  `R` is a simple character vector containing the file reference of the external array associated with the variable named by `Y`, or the null vector if there is no associated external array.

## Example
```apl
      ⎕XT'V'
EXT\ARRAY
 
      ⍴⎕XT'G'
0
 
```

!!! Info "Information"
    Support for external variables has been deprecated, and they are scheduled for removal in a future release. For information on how to identify uses of external variables in your existing codebase, see the [Release Notes](../../../release-notes/announcements/deprecated-functionality/).


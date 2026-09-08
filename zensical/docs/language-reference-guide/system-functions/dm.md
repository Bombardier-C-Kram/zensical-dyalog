---
search:
  boost: 2
---
<!-- Hidden search keywords -->
<div style="display: none;">
  ⎕DM DM
</div>






# Diagnostic Message

```apl
R←⎕DM
```



This niladic function returns the last reported APL error as a three-element vector, giving error message, line in error and position of caret pointer.

## Example
```apl

      2÷0
DOMAIN ERROR
      2÷0
     ^

      ⎕DM
 DOMAIN ERROR        2÷0       ^
```


Note: `⎕SIGNAL` can be used to reset the value of this system constant.




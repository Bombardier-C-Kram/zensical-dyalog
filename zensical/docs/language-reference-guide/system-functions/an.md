---
search:
  boost: 2
---
<!-- Hidden search keywords -->
<div style="display: none;">
  ⎕AN AN
</div>






# Account Name

```apl
R←⎕AN
```



This is a simple character vector containing the user (login) name. Under UNIX and Linux this is the real user name, whereas `⎕AI` returns the effective user id.

## Example
```apl
      ⎕AN
Pete
 
      ⍴⎕AN
4
```




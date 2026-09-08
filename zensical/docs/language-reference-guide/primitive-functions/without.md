---
search:
  boost: 2
---
<div style="display: none;">
  ~ without
</div>

# Without

```apl
R←X~Y
```

`X` must be a scalar or vector.  `R` is a vector of the elements of `X` excluding those elements which occur in `Y` taken in the order in which they occur in `X`.

Elements of `X` and `Y` are considered the same if `X≡Y` returns 1 for those elements.

`⎕CT` and `⎕DCT` are  implicit arguments of Without. Without is also known as Excluding.

## Examples
```apl
      'HELLO'~'GOODBYE'
HLL
      'MONDAY' 'TUESDAY' 'WEDNESDAY'~'TUESDAY' 'FRIDAY'
 MONDAY  WEDNESDAY
 
      5 10 15~⍳10
15
```

For performance information, see [Programmer's Guide: "Search Functions and Hash Tables"](../../../programming-reference-guide/introduction/search-functions-and-hash).

---
search:
  boost: 2
---
<div style="display: none;">
  ⍨
  constant
</div>






# Constant

```apl
R←{X}(A⍨)Y
```



`A`,  `X` and `Y` are arrays. The Constant operator returns array `A`.

## Examples
```apl

      'mu'⍨ 'any' ⎕NULL   ⍝ Always returns its operand
mu
      1E100 ('mu'⍨) 1j1
mu
      ¯1⍨¨ ⍳2 3
¯1 ¯1 ¯1
¯1 ¯1 ¯1

```




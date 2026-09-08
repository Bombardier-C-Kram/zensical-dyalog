---
search:
  boost: 2
---
<div style="display: none;">
  - negate
</div>

# Negate {: #negative}

```apl
R←-Y
```

`Y` may be any numeric array. `R` is numeric and is the negative value of `Y`. For complex numbers both the real and imaginary parts are negated.

## Example
```apl
      -4 2 0 ¯3 ¯5
¯4 ¯2 0 3 5
 
      -1j2 ¯2J3 4J¯5
¯1J¯2 2J¯3 ¯4J5
```




---
search:
  boost: 2
---

<!-- Hidden search keywords -->
<div style="display: none;">
  2023⌶
</div>

# Close All Windows

```apl
R←2023⌶Y
```

Under Windows the option, *Windows -> Close All Windows* allows the user to close all open Editor and Tracer Windows, but does not reset the *state indicator*.

This I-beam mimics this behaviour, thus allowing the user to write code which can close all windows before attempting to save the workspace; with the exception of calling `0 ⎕SAVE` it is not possible to save a workspace if any editor or tracer windows are open.

Under non-Windows operating systems this is the only mechanism for closing all such windows. This I-beam is effective in Ride too.

## Example
```apl
      2023⌶0    
```

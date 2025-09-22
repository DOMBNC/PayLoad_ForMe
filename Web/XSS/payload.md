## Encoding Sniffing
- A good example is putting UTF-7 (7-bit Unicode with
  Base-64'd blocks denoted by +..-) text into XSS payloads. 
```
 +ADw-script+AD4-alert(1);+ADw-/script+AD4-
 ```

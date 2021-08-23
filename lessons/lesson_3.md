### Exercise 3: Matching Characters

| Match | Text |
| ----- | :--: |
| Match | can  |
| Match | man  |
| Match | fan  |
| Skip  | dan  |
| Skip  | ran  |
| Skip  | pan  |

### Solution

```
/{can|man|fan}/g
/([c|m|f]an)/g
/[cmf]an/g
/[^drp]an/g
```

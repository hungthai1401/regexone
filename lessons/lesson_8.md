### Exercise 8: Matching Optional Characters

| Match |      Text       |
| ----- | :-------------: |
| Match |  1 file found?  |
| Match |  2 file found?  |
| Match | 24 files found? |
| Skip  | No files found. |

### Solution

```
/\d+ file[s]? found[?]/g
```

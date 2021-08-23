### Exercise 4: Excluding Characters

| Match | Text |
| ----- | :--: |
| Match | hog  |
| Match | dog  |
| Skip  | bog  |

### Solution

```
/[hd]og/g
/[^b]og/g
```

### Exercise 7: Matching Repeated Characters

| Match |  Text   |
| ----- | :-----: |
| Match | aaaabcc |
| Match | aabbbbc |
| Match |  aacc   |
| Skip  |    a    |

### Solution

```
/a{2,}b{0,}c{1,}/g
/aa+b*c+/g
```

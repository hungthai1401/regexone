### Exercise 6: Matching Repeated Characters

| Match |   Text    |
| ----- | :-------: |
| Match | wazzzzzup |
| Match |  wazzzup  |
| Skip  |   wazup   |

### Solution

```
/waz{2,}up/g
```

### [Exercise 6](https://regexone.com/lesson/repeating_characters): Matching Repeated Characters

| Match |   Text    |
| ----- | :-------: |
| Match | wazzzzzup |
| Match |  wazzzup  |
| Skip  |   wazup   |

### Solution

```
/waz{2,}up/g
```

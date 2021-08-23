### [Exercise 5](https://regexone.com/lesson/character_ranges): Matching Character Ranges

| Match | Text |
| ----- | :--: |
| Match | Ana  |
| Match | Bob  |
| Match | Cpc  |
| Skip  | aax  |
| Skip  | bby  |
| Skip  | ccz  |

### Solution

```
/[A-C][n-p][a-c]/g
```

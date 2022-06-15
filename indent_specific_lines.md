## How to indent specific line numbers

```
:[range]normal >>
```

eg:
```
1 line one
2 line two
3 line three
4 line four
```
`:2,3normal >>`
```
1 line one
    2 line two
    3 line three
4 line four
```

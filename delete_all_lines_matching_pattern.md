## How to delete all lines matching a pattern

```
:g/pattern/d
```

eg:
```
1 line one
2 line two
3 line three
4 line two
5 line four
```
`:g/two$/d`
```
1 line one
3 line three
5 line four
```

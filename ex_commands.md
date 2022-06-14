## Delete lines anywhere in the file and optionally put them in register x

```
:[range]delete[x]
```

eg:
```
1 line one
2 line two
3 line three
4 line four
```
`:2,3d`
```
1 line one
4 line four
```

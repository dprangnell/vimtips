## How to copy specific line numbers to a specific destination

```
:[range]copy{destination}
# OR:
:[range]t{destination}
```

eg:
```
1 line one
2 line two
3 line three
4 line four
5 line five
6 line six
```
`:2,3t5`
```
 1 line one
 2 line two
 3 line three
 4 line four
 5 line five
 2 line two
 3 line three
 6 line six
```

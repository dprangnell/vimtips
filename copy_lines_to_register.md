## How to copy lines to a named register

Registers are vim's memory slots.  By copying some lines to a register, you can access them later with other ex commands such as put.

This is useful when the lines you are copying are off screen from where you are pasting them.

```
:[range]yank register
:[range]y register
```

eg:
```
1 line one
2 line two
3 line three
4 line four
```
`:2,3y j`
```
1 line one
2 line two
3 line three
4 line four
```
`3pu j` or `3put j`
```
1 line one
2 line two
3 line three
2 line two
3 line three
4 line four
```

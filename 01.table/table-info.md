## Align columns
```
:%!column -t
```

## Sort by second column
```
:%!sort -k1
```

## Create macros
```
@t
^3wyef/vephhhhhcw=2023-"jjj^
^ - start line
3wye - go to year and copy
f/vep - go to // and paste instead
hhhhcw - go to start of pasted year, remove and go to insert mode
<C-r>=2023-<C-r><CR> - insert difference
jj - escape
j^ - next line and go to start of line
```

## comand line start from line 2 to the end
```
:2,$ normal @t
```

### 1. indexing and slicing

Use indexing notation to slice items from a list or string. Syntax: `list[i:j]` where i is the starting index and j is the stopping index. 

```py
test = [1, 2, 3, 4, 5, 6]
test = test[0:2]
print(test)

# Output: [1, 2]
```

Use slicing in a `for` loop by adding a numeric value to i. This designates the stopping point as (x) amount + i.

```py
var = 'abcd'
for i in range(len(var)):
    print(var[i:i+3])
    
# Output: abc
# Output: bcd
# Output: cd
# Output: d
```

Use negative numbers to begin at the ending index: `test[-1]`

Leave the starting or ending index empty to designate as either the first or last index: `test[:5]` or `test[5:]` 

### 2. Change or delete list items with indices

Use a list index to change the item in a list. A negative index number begins at the end of the list. 


```py
test = [1, 2, 3, 4, 5, 6]
test[0] = 'A'
test[-1] = 'F'
print(test)

# Output: ['A', 2, 3, 4, 5, 'F']
```
Use the `del` keyword to delete a list item. 

```py
test = [1, 2, 3, 4, 5, 6]
del test[0]
del test[-1]
print(test)

# Output: [2, 3, 4, 5]
```

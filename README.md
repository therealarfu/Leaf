# Leaf Language 
It's a programming language still in development

### Extension: 
> file.lf

# Variables
> ``[Type](Optional) [Name] = [Content]``

## Types:
**integer** -> ``int [Variable] = 1``

**float** -> ``float [Variable] = 1.5``

**string** -> ``string [Variable] = "Hello, World!"``

**list** -> ``list [Variable] = [1,2,3,4]``

**object** -> ``obj [Variable] = {"Hello": "World"}``

**variant** -> ``[Variable] = anything``

# Conditionals
> ``if ([Condition]) { [Content] } elseif ([Condtion]) { [Content] } else { [Content] }``

## Example

```
int x = 10

if (x < 10) {
  print("Less than 10")
}
elseif (x == 10) {
  print("Equal to 10")
}
else {
  print("More than 10")
}
```

# For

> ``for ([Variable] = [Start], [Variable] = [End], [Step]) { [Content] }``

## Example
```
for (i = 0, i = 10, i ++) {
  print(i)
}
```

# While

> ``while ([Condition]) { [Routine] }``
## Example
```
int i = 0
while (i < 10){
  print(i)
  i++
}
```

# Functions

> ``[Type] [Name] ([Parameters]) {[Content]}``

## Examples

```
int sumTwo(int num1, int num2){
  return num1 + num2
}
```

```
items = [1,2,3,4,5]
result = 0

void sumList(list arr, int sum){
  for (i = 0, i = len(arr) - 1, i++){
    sum += arr(i)
  }
}
```

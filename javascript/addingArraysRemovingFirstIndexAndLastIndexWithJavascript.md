# adding arrays, removing first index and last index with javascript
To add an array in javascript later, we can use the function ".push(newIndex)"

Example
```javascript
var newArray = [2,5,6]
#output = [2,5,6]
newArray.push(10)
#output = [2,5,6,10]
```
Now, to remove an initial item we can use the ".shift" function. It will remove the first Array

Example
```javascript
var newArray = ["banana", "Maçã", "Laranja"]
#output = ["banana", "Maçã", "Laranja"]
newArray.shift()
#output = ["Maçã", "Laranja"]
```
In the same example, we can use the ".pop" function to remove the last item from the list

Example
```javascript
var newArray = ["banana", "Maçã", "Laranja"]
#output = ["banana", "Maçã", "Laranja"]
newArray.pop()
#output = ["banana", "Maçã"]
```

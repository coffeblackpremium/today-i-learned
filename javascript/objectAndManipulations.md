# JavaScript Object and your manipulation

in JavaScript we can make and construct objects with the second example

```javascript
const myDogs = {
    name: 'Pitoco, cara preta',
    legs: 4,
    tails: 1,
    friends: ['Joao', 'My Mom'],
}
```
For those who studied Python, this could be translated as "Dictionary".

# How to think about this solution

We think of objects in javascript as if they were real life. For example, a mouse. Each mouse has its characteristic and its 'metadata'. This makes it much easier to understand

# Acessing Nested Objects

We can access an object using square brackets '[]' or '.'

On different occasions, we must be forced to use the Brackets to access a certain data to change its value.

example

```javascript
const myStorage = {
  "car": {
    "inside": {
      "glove box": "maps",
      "passenger seat": "crumbs"
     },
    "outside": {
      "trunk": "jack"
    }
  }
};

const gloveBoxContents = myStorage.car.inside['glove box']

```
In this example, I accessed Object 'myStorage' using '.' and bracket.
this is an example of using the square brackets and dots
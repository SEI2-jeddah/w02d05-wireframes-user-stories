# Array Methods



## Foreach
```javascript
let arr = ["Ebere", "Ahmad", "Yassir", "Atheer"]
arr.foreach(function(element){
  console.log(`The instructional team consists of ${element}`)
})

```

## Map
```javascript
let arr = ["Ebere", "Ahmad", "Yassir", "Atheer"]
let mappedArr = arr.map(function(element){
  return element.charAt(0)
})

console.log(arr) //["Ebere", "Ahmad", "Yassir", "Atheer"]
console.log(mappedArr) // ["E", "A", "Y", "A"]

```

## Filter
```javascript
let arr = [ 5, 12, 200, 20, 1,4]
let filteredElements = arr.filter(function(element){
  return element > 12
})

// console.log(arr) [ 5, 12, 200, 20, 1,4]
// console.log(filteredElements) [20, 200]
```

## Find
```javascript
let arr = ["Ebere", "Ahmad", "Yassir", "Atheer"]
let foundElement = arr.find(function(element){
  return element == "Ebere"
})

//returns Ebere

```

## FindIndex
```javascript
let arr = ["Ebere", "Ahmad", "Yassir", "Atheer"]

let findIndex = arr.findIndex(function(element){
  return element == "Ebere"
})

//returns 0
```

## Reduce
```javascript
let arr = [1,2,4,5]
//get sum of elements in array
let sum = arr.reduce(function(accumulator, element){
  return accumulator + element
}, 0)

// console.log(arr) [1,2,4,5]
// console.log(sum) 12
```s


Why map, filter, reduce?
One of the key foundations of functional programming is its use of lists and list operations. In Javascript we have map, filter and reduce, all functions that given an initial list (array of things), transform it into something else, while keeping that same original list intact.

### Additional Resources

- [Array Methods and examples](https://medium.com/@joomiguelcunha/learn-map-filter-and-reduce-in-javascript-ea59009593c4)
- [Codeburst](https://codeburst.io/all-about-javascript-arrays-44d2d36874b9/)

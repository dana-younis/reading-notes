# Passing Functions as Props


## React Docs - lists and keys

* What does .map() return?

***function to take an array of numbers and double their values. We assign the new array returned by map() to the variable doubled and log it***



* If I want to loop through an array and display each value in JSX, how do I do that in React?
***using the JavaScript map() function***


* Each list item needs a unique _key___.


* What is the purpose of a key?

***Keys help React identify which items have changed, are added, or are removed. Keys should be given to the elements inside the array to give the elements a stable identity***
 


## The Spread Operator






* What is the spread operator?
 ***is a new addition to the set of operators in JavaScript ES6. It takes in an iterable (e.g an array) and expands it into individual elements. The spread operator is commonly used to make shallow copies of JS objects. Using this operator makes the code concise and enhances its readability***

* List 4 things that the spread operator can do.

- Concatenating  arrays
- Using Math function
- combining arrays or objects
- Add to state in React



* Give an example of using the spread operator to combine two arrays.

const cars = ['🚗', '🚙'];
const trucks = ['🚚', '🚛'];

const combined = cars.concat(trucks);
// [ '🚗', '🚙', '🚚', '🚛' ]

console.log(cars); // ['🚗', '🚙'];
console.log(trucks); // ['🚚', '🚛'];


* Give an example of using the spread operator to add a new item to an array.

const fewFruit = ['🍏','🍊','🍌']
const fewMoreFruit = ['🍉', '🍍', ...fewFruit]
console.log(fewMoreFruit) //  Array(5) [ "🍉", "🍍", "🍏", "🍊", "🍌" ]

* Give an example of using the spread operator to combine two objects into one.

const objectOne = {hello: "🤪"}
const objectTwo = {world: "🐻"}
const objectThree = {...objectOne, ...objectTwo, laugh: "😂"}
console.log(objectThree) // Object { hello: "🤪", world: "🐻", laugh: "😂" }
const objectFour = {...objectOne, ...objectTwo, laugh: () => {console.log("😂".repeat(5))}}
objectFour.laugh() // 😂😂😂😂😂





## How to Pass Functions Between Components






* In the video, what is the first step that the developer does to pass functions between components?
***create the function wherase Pass Data from Child to Parent by  the state ***
 

* In your own words, what does the increment function do?
***add one  ***


* How can you pass a method from a parent component into a child component?



* How does the child component invoke a method that was passed to it from a parent component?




## Things I want to know more about

## References

# Putting it all together


## React Docs - thinking in React

* How would you break a mock into a component heirarchy?
- FilterableProductTable (orange): contains the entirety of the example
- SearchBar (blue): receives all user input
- ProductTable (green): displays and filters the data collection based on user input
- ProductCategoryRow (turquoise): displays a heading for each category
- ProductRow (red): displays a row for each product



* What is the single responsibility principle and how does it apply to components?

* How do you understand single responsibility principle?
***The single responsibility principle (SRP) states that every class or module in a program should have responsibility for just a single piece of that program's functionality. Further, the elements of that responsibility should be encapsulated by the responsible class rather than spread out in unrelated classes.***




* What does it mean to build a ‘static’ version of your application?
 
***The components will only have render() and no interactivity***



* Once you have a static application, what do you need to add?
***to add the states***

* What are the three questions you can ask to determine if something is state?
***Is it passed in from a parent via props? If so, it probably isn’t state.***
***Does it remain unchanged over time? If so, it probably isn’t state.***
***Can you compute it based on any other state or props in your component? If so, it isn’t state.***


* How can you identify where state needs to live?
- Identify every component that renders something based on that state.
- Find a common owner component (a single component above all the components that need the state in the hierarchy).
- Either the common owner or another component higher up in the hierarchy should own the state.
- If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.



## Things I want to know more about


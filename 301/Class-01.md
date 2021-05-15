# Introduction to React and Components


## Component Based Architecture

* What is a component?

 - ***A component is a modular, portable, replaceable, and reusable set of well-defined functionality. It has an obviously defined interface and conforms to a recommended behavior. A software component can be deployed independently and is subject to composition by third parties.***


* What are the charactistics of a component?
 
- Reusability – Components are normally built to be recycled in various circumstances. modules
- Replaceable - Modules with identical components can be freely replaced.
- Not context specific − Components may function in various environments and contexts. Components
- Extensible − A feature can be expanded to provide new behavior from existing modules.
- Encapsulated − A component shows the interfaces that enable the caller to use its functions, which does not     display internal process information or internal variables or states.
- Independent − Modules have a minimum dependency on other components.



* What are the advantages of using component based architecture? 
 *** Components implement well-known interfaces to provide defined functionality. The use of third-party components allows you to spread the cost of development and maintenance. Reliability increases since the overall system reliability increases since each individual component enhances the reliability of the whole system. Easy to change and update the implementation without affecting the rest of the system. Productivity for the software development and future software development. *** 
 - Ease of deployment
 - Reduced cost 
 - Ease of development
 - Reusable
 - Modification of technical complexity
 - Reliability
 - System maintenance and evolution
 - Independent
 


## What is Props and How to Use it in React
***React is a component-based library which divides the UI into little reusable pieces.                         Props is a special keyword in React, which stands for properties and is being used for passing data from one component to another.uni-directional flow *** 

* What is props short for?
***short for theatrical property, an object used during a theatrical performance *** 

* How are props used in React?
- First, define a characteristic and its value (data)
***With interpolation, we can specify our attributes & assign values to them ;declaring a “text” attribute to the ChildComponent and then assign a string value ***


- Then move it through Props to child component(s).
***It's really easy to pass props. We pass props into a react component and props all required information as we pass arguments into a feature.***
- Lastly, make proposals Data Data
***we will render the props object by using string interpolation(console.log(props);)                                The notation dot(.) can be used to view object components .                                                        Each ChildComponent now gives prop data of its own. So we can use Props to transfer data and to transform static components to dynamic components.***


* What is the flow of props?
***uni-directional flow. one way from parent to child,props data is read-only, which means that data coming from the parent should not be changed by child components.***




## Things I want to know more about

## References
[Component Based Architecture](https://www.tutorialspoint.com/software_architecture_design/component_based_architecture.htm)
[What is Props and How to Use it in React](https://itnext.io/what-is-props-and-how-to-use-it-in-react-da307f500da0#:~:text=%E2%80%9CProps%E2%80%9D%20is%20a%20special%20keyword,way%20from%20parent%20to%20child)
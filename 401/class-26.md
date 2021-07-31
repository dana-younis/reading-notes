# Component Based UI

## Name 5 Javascript UI Frameworks (other than React)

- Angular JS
- Vue JS
- Ember
- Svelte
- Ext

## What’s the difference between a framework and a library?

Framework: provide us with all the basic needs (skelton) of we need to build apps, and it contain using libraries. example: Express, React
Library: do so specific task in your code, and you call it whenever you want. example: JQuery.

The key difference between a library and a framework is "Inversion of Control". When you call a method from a library, you are in control. But with a framework, the control is inverted: the framework calls you. Both of them define an API for programmers to use.

## State:

Is an object (instance) from the main React component, and it has properties that change and control the behavior of the main component.

Which 3 things had you heard about previously and now have better clarity on?
React, State and a component.

Which 3 things are you hoping to learn more about in the upcoming lecture/demo?
React.js, using component with different states.

What are you most excited about trying to implement or see how it works?
Implementing React JS

```
const element = <h1>Hello, world</h1>;
ReactDOM.render(element, document.getElementById('root'));
```

React elements are immutable (unable to change) and the only way to change element is by calling ReactDOM.render() many times:

- **What’s the difference between a framework and a library?**

## Document the following Vocabulary Terms

- **Rendering:** is the process of generating a photorealistic or non-photorealistic image from a 2D or 3D model by means of a computer program.

- **Templates:** is a generic class or other unit of source code that can be used as the basis for unique units of code. In C++, an object-oriented computing language, there are Standard Template Libraries from which programmers can choose individual template classes to modify.

- **State:** In information technology and computer science, a system is described as stateful if it is designed to remember preceding events or user interactions, the remembered information is called the state of the system.

## Preparation Materials

### JSX

- **Why JSX?**

React embraces the fact that rendering logic is inherently coupled with other UI logic: how events are handled, how the state changes over time, and how the data is prepared for display.

- ### Embedding Expressions in JSX

You can put any valid JavaScript expression inside the curly braces in JSX. For example, 2 + 2, user.firstName, or formatName(user) are all valid JavaScript expressions.

- ### JSX is an Expression Too

After compilation, JSX expressions become regular JavaScript function calls and evaluate to JavaScript objects, this means that you can use JSX inside of if statements and for loops, assign it to variables, accept it as arguments, and return it from functions.

- ### Specifying Attributes with JSX

You may use quotes to specify string literals as attributes, You may also use curly braces to embed a JavaScript expression in an attribute, Don’t put quotes around curly braces when embedding a JavaScript expression in an attribute. You should either use quotes (for string values) or curly braces (for expressions), but not both in the same attribute.

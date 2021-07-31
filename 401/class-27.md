# useState() Hook

- How does React differ from vanilla JS/HTML/CSS?

React provides a HTML/CSS framework in order to build interfaces with components. With vanilla JS/HTML/CSS, you build all that from scratch yourself. React even provides the training wheels for you to add a favicon. React is much more scalable.

- What is the primary difference between a function component and a class component?

You have to extend a class component and use `this.`, whereas you set the state in a functional component.

## Document the following Vocabulary Terms:

- Functional Components

Stateless, can be created with a `function abc` syntax or implied with an arrow function. Accept and use props, and don't use `render()`.

- Children / Child Components

Child components are nested components that inherit props from their parent.

```JS
//  3rd party resources
import React from 'react';

//  esoteric resources
import Child from './child';

function Parent() {
  return(
    <>
      <Child/>
      <Child/>
      <Child/>
    <>
  )
}

```

In this case the parent component ('Parent') is responsible for rendering children components ('Child'). Most importantly parent components act as a shared common ancestor.

### Preview and Preparation

- Functional components improve performance
- Class components lead to spaghetti code at a certain point
- Functions are easier to read
- Prevent unnecessary nesting (more classes to solve class problems)

```JS

class Example extends React.Component {
  constructor(props) {
    super(props);
    this.state = {
      count: 0
    };
  }

  render() {
    return (
      <div>
        <p>You clicked {this.state.count} times</p>
        <button onClick={() => this.setState({ count: this.state.count + 1 })}>
          Click me
        </button>
      </div>
    );
  }
}

```

## vs

```JS
import React, { useState } from 'react';

function Example() {
  // Declare a new state variable, which we'll call "count"
  const [count, setCount] = useState(0);

  return (
    <div>
      <p>You clicked {count} times</p>
      <button onClick={() => setCount(count + 1)}>
        Click me
      </button>
    </div>
  );
}

```

# Context API

## Describe use cases for `useState()` and `useReducer()`
the useState updater function is newly called on each render. What it means is that when you have a complex logic to update state, you simply won’t use the setter directly to update state; instead, you will write a complex function, which in turn would call the setter with updated state.

`useReducer()` is preferred over `useState()` when we have complex state logic or instances when state changes are progressive. It works well with the following example situations:

- JavaScript objects or arrays as state
- complex state transitions
- differing but intertwining properties that should be managed in one state object

## Why do custom hooks need the use prefix?

The name of any custom hook should begin with `use`. This convention indicates to developers that hooks are used within the file/custom hook.

## What do custom hooks usually do?

They allow the creation of modular functionality, usable across multiple components, with the advantage of being able to 'hook' into the React API for things like state and component lifecycle.

## Using any list of custom hooks, research and name one that you think will be useful in your applications

This is a toss-up for me between `useFormState` and `constate`. I really like the simplicity of useFormState, and I am sure I will use it at some point, but being able to use constate to share state across components definitely sounds good to me.

## Describe how a hook that fetches API data might work

The hook might take in a url, a method, and a body. Using axios or something similar, useState and possibly useEffect, an API call can be made based on and using the parameters passed in and then an objects state could be 'set' based on the results of the API call.
## Document the following Vocabulary Terms

1. reducer : is a function that determines changes to an application's state. It uses the action it receives to determine this change.

* Which 3 things had you heard about previously and now have better clarity on?

   1. reducer  .
   2. useMemo.
   3. redux.

* Which 3 things are you hoping to learn more about in the upcoming lecture/demo?

1. the proper usage of context .
2. useful custom-hooks packages  .
3. useCallBack and useMemo  as the examples in the reads are really poor .

What are you most excited about trying to implement or see how it works? optimizing the code and why do i need context and who to use them .


Creates a Context object with React.createContext. React will read the current context value from the closest matching Provider above it in the tree when rendering a component that subscribes to this Context object.
A Provider React component is included with every Context object, allowing consuming components to subscribe to context changes.
When a component doesn't have a matching Provider above it in the tree, the defaultValue parameter is utilized. This default value might be useful for testing components without enclosing them in a container. Note that providing undefined as a Provider value does not force defaultValue to be used by consuming components.

If just the Avatar component need the user and avatarSize properties, it may seem unnecessary to pass them down through several layers. It's also inconvenient because if the Avatar component requires additional props from the top, you must also add them to all intermediate levels.
## Vocabulary Terms

**reducer**        _manages state in an application. A reducer is a function which takes two arguments -- the current state and an action -- and returns based on both arguments a new state.
**Caveats**
There are several gotchas that might cause accidental renderings in consumers when a provider's parent re-renders since context utilizes reference identity to determine when to re-render. (This is a link to another website.)
**Globally Accessible**
Accessible from everywhere in the world
A single centralized component may control the status of our snackbars (which ones are shown).
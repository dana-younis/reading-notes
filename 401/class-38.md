# Redux - Asynchronous Actions



### How granular should your reducers be?

it should be pure functions with no side-effects

### Pro or Con – multiple reducers can “fire” when a commonly named action is dispatched

is a pro thing because it will help in letting reducers communicate with each other in kind a way.

### Name a strategy for preventing the above

using different actions.

### store :

is where the initial state, reducer and actions are placed in one place in Redux.

### combined reducers:

is the process of using more than one reducer in our store.

---

## Redux MiddleWares :

Redux also allows for middleware that sits between an action being dispatched and the action reaching the reducers.

### Redux Thunk MiddleWare :

Redux Thunk is a middleware that lets you call action creators that return a function instead of an action object. That function receives the store’s dispatch method, which is then used to dispatch regular synchronous actions inside the function’s body once the asynchronous operations have been completed.

You can only make simple synchronous changes with a basic Redux store by dispatching an action. Middleware enhances the capabilities of the store and allows you to create async logic that interacts with it. (A thunk is a programming notion in which a function is used to postpone an operation's evaluation/calculation.)

`npm install redux-thunk@2.3.0`


* ***Redux Async Data Flow***

So how do middleware and async logic affect the overall data flow of a Redux app?

We must first handle a user event in the program, such as a button click, just as we would with any other action. Then we call dispatch() with anything to send in, whether it's a simple action object, a method, or another item that a middleware can check for.
Once that dispatched value reaches a middleware, it can make an async call, and then dispatch a real action object when the async call completes.



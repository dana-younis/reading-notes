# Redux - Additional Topics

## Review, Research, and Discussion

* **What’s the best practice for “pre-loading” data into the store (on application start) in a Redux application?**

The best practice is to wrap the opening pre-load in useEffect. With this, you need to take the function outside of the props that you passed into the component.

* **When using a thunk/async action that dispatches the actual action, which do you export from your reducer?**

You will still be exporting the new data to replace the state from the reducer. The action calling the reducer will be sent as a function rather than an object.

## Document the following Vocabulary Terms

* **middleware:** In Redux, middleware provides a third-party extension point between the when an action is dispatched and the moment it reaches the reducer. It needs to be used for asynchronous calls with Redux.

* **thunk:** Thunk is a redux middleware that allows you to do async functions in conjunction with Redux.

## Preparation Materials

### Redux Toolkit

* **Purpose**
The Redux Toolkit package is intended to be the standard way to write Redux logic. It was originally created to help address three common concerns about Redux:

* "Configuring a Redux store is too complicated"
* "I have to add a lot of packages to get Redux to do anything useful"
* "Redux requires too much boilerplate code"

We won't be able to address every use case, but in the spirit of create-react-app and apollo-boost, we can aim to give some tools that abstract over the setup process and handle the most frequent use cases, as well as some useful utilities to help users simplify their application code.

Redux Toolkit also comes with a strong data fetching and caching feature called "RTK Query." It comes as a distinct set of entry points in the package. It's optional, however it can help you avoid having to implement data fetching logic by hand.

These tools should be beneficial to all Redux users. Whether you're a brand new Redux user setting up your first project, or an experienced user who wants to simplify an existing application, Redux Toolkit can help you make your Redux code better.


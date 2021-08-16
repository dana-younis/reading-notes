# `<Login />` and `<Auth />`

**Why is the Context API useful?**  
The Context API is useful because it can change important values for many components at once from a centralized location, without all of the values having to be passed through many layers of props.

**Can a component outside of a provider get its context?**  
It needs to be in a provider, or in a component whose parent is wrapped in the provider.

**What are some common use cases for using the Context API?**  
It can be used to show who is logged in and what authorizations they have.

**Describe “Context Hell”**  
Without useContext, you many have to pass props through many layers of components to get info to the right place. This can be frustrating and can lead to easy to miss mistakes.

## Vocabulary Terms

- **Global state**: Keeping a state at the top level of an application and providing access methods to all child levels without the need to pass props. Global state should only keep states that concern the entire app, such as theme, language, or other app-wide settings. (source: [React blog](https://react.christmas/2019/7))
- **Global context**: Context provides a way to share values and data between components without having to explicity pass a prop through every level of the tree. Designed to share data that can be considered "global" for a tree of React components, such as the current authenticated user, theme, or preferred language. (source: [context in React docs](https://reactjs.org/docs/context.html))
- **Provider**: Every Context object comes with a Provider React component that allows consuming components to subscribe to context changes. Provider component accepts a value prop to be passed to consuming components that are descendants of this Provider. One Provider can be connected to many consumers. Providers can be nested to override values deeper within the tree. (source: [Context.Provider in React docs](https://reactjs.org/docs/context.html#contextprovider))
- **Consumer**: Consumers are decendants of a Provider that will re-render whenever the Provider's value prop changes. The propagation from Provider to its descendant consumers (including `.contextType` and `useContext`) is not subject to the `shouldComponentUpdate` method, so the consumer is updated even when an ancestor component skips an update.
  | Term | Definition |
  | -------------- | --------------------------------------------------------------------------------------------------------------------------------------- |
  | global state | This is the state of the entire React application. |
  | gloabl context | This is context that affects the entire application, and it will share data to everything in the React component tree. |
  | provider | The context provider accepts a value that will be passed to its children. All children components will rerender when the value changes. |
  | consumer | This is a React component that subscribes to context changes in value of the Provider. |

  what is role based access control?

RBAC, or role-based access control, restricts network access based on a person's function inside an organization and has become one of the most popular approaches for advanced access control. The degrees of access that employees have to the network are referred to as roles in RBAC.
EXAMPLES OF ACCESS CONTROL BASED ON ROLE
Management role scope – it limits what objects the role group is allowed to manage.
Management role group – you can add and remove members.
Management role – these are the types of tasks that can be performed by a specific role group.
Management role assignment – this links a role to a role group.
BENEFITS OF RBAC

IT support and administrative duties are being reduced.
Increasing operational effectiveness
Improving adherence
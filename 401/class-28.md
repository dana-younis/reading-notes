[*HOME*](https://nassir1976.github.io/reading-notes/)

## Readnote-31  Hooks API

### Review, Research, and Discussion

1- Why do we not need more .html pages in a multi-page React app?
- In a multi-page react app, we don't need any additional html pages since we can use a browser router to render certain components on separate pathways using a browser router. This is due to the way React handles the DOM.

- Instead of several pages, create a website with various paths. Because React isn't built for building multi-page websites. To manage numerous views, we'll need to construct several routes.



- create-react-app is a wonderful method to get a new react app up and running quickly, complete with **webpack, live reloading, and more**. However, it doesn't give a means to supply various index.html pages with different entry points.
2- If we wanted a component to show up on every page, where would we put it and why?
  - Outside the <BrowserRouter/>
  - Inside the <BrowserRouter />, outside a <Route />
  - inside a <Route />
- to rendered a components to show up on every page we have to put it in the **browserRouter**  but it shoud  be **outside** of specific **Route** 

3- What does props.children contain?
  - props. children is used to display any data  between the opening and closing tags when invoking a component. 

### Document the following Vocabulary Terms

- Composition
   - React Composition is a development pattern based on React's original component model where we build components from other components using explicit defined props or the implicit children prop.


  

**Children / Child Components:** 
 "Children allow you to pass components as data to other components, just like any other prop you use."

Once again, children don't have to be components, they could be many things in React. Even if we wanted to fetch data from a server, we can do it by using a function-as-a-child pattern. After all, we can pass any JavaScript expression as children.
- Children, like any other prop, enable you to transmit components as data to other components. ... Children are unique in that React offers support for them via its ReactElement API and JSX. Children from XML are a wonderful match for children from React.

**Hash Routing:** 
This type of routing is considered to be server side and uses the anchor part of the URL to simulate different content. This router is mainly used for static websites with a server that only responds to requests for files that it knows about.
"HashRouter uses a hash symbol in the URL, which has the effect of all subsequent URL path content being ignored in the server request."

**Link Routing:** 
Link routing utilizes the `<Link>` component. This is a wrapper around anchor tags, but has the added benefit that it automatically knows where our components are and it can adjust the style of a link to make it look active when it's the page the user is currently browsing. 
Basically, this form of routing uses hyperlinks to travel between different areas of an application. This component has the ability to adjust the URL and alter the UI.
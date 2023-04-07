### Conceptual Exercise

Answer the following questions below:

- What is React? When and why would you use it?
The React. js framework is an open-source JavaScript framework and library developed by Facebook. It's used for building interactive user interfaces and web applications quickly and efficiently with significantly less code than you would with vanilla JavaScript

- What is Babel?
Babel is a free and open-source JavaScript transcompiler that is mainly used to convert ECMAScript 2015+ code into backwards-compatible JavaScript code that can be run by older JavaScript engines.

- What is JSX?
JSX is an extension to the JavaScript language syntax which provides a way to structure component rendering using syntax familiar to many developers commonly used in React. It is similar in appearance to HTML.

- How is a Component created in React?
As the React docs tell us, “The simplest way to define a component is to write a JavaScript function”. This is a normal JavaScript function except that it returns a JSX React element.

- What are some difference between state and props?
 State is the local state of the component which cannot be accessed and modified outside of the component. It's equivalent to local variables in a function. Props, on the other hand, make components reusable by giving components the ability to receive data from their parent component in the form of props.

- What does "downward data flow" refer to in React?
What does "downward data flow" refer to in React? Downward data flow is the idea that parent components pass data down to their children via props. In order to make data go the other way, we have to pass a. function down from the parent that the child can then call with some information.

- What is a controlled component?
In React, a controlled component is a component that is controlled by React state, while an uncontrolled component is a component that maintains its own internal state. A conteusable functions that a React JS software developer can use to add special and unique functionality to the React applications. Usually, if there is a requirement to add a feature, one can install a third-party library and solve the problem.rolled component receives its current value and an update callback via props, and the parent component manages the state of the component

- What is an uncontrolled component?
Uncontrolled components refer to components that manage their own state internally. They use a ref to access the DOM element's current value and update the state accordingly. A controlled functional component is a component that receives its current value and update callback via props.

- What is the purpose of the `key` prop when rendering a list of components?
React's key prop gives you the ability to control component instances. Each time React renders your components, it's calling your functions to retrieve the new React elements that it uses to update the DOM. If you return the same element types, it keeps those components/DOM nodes around, even if all the props changed

- Why is using an array index a poor choice for a `key` prop when rendering a list of components?
It is not recommended to use the index of the array as the key prop if you know the array will not be static. If the key is an index, reordering an item in the array changes it. Then React will get confused and re-render the incorrect element.

- Describe useEffect.  What use cases is it used for in React components?
React will remember the function you passed (we'll refer to it as our “effect”), and call it later after performing the DOM updates.


- What does useRef do?  Does a change to a ref value cause a rerender of a component?
difference is that when that value changes, it doesn't cause a re-render.

- When would you use a ref? When wouldn't you use one?
Managing focus, text selection, or media playback. Triggering imperative animations.

- What is a custom hook in React? When would you want to write one?

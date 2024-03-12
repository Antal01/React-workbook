# react-workbook  

1. **What is React?**
   - React is a JavaScript library for building user interfaces, particularly for single-page applications where the UI needs to be highly dynamic and responsive.

2. **Explain the concept of Virtual DOM in React.**
   - The Virtual DOM is a lightweight copy of the actual DOM in memory. React uses it to improve performance by minimizing direct manipulation of the real DOM, updating only the necessary parts when there's a change, and then efficiently updating the actual DOM.

3. **What is JSX in React?**
   - JSX (JavaScript XML) is a syntax extension for JavaScript that looks similar to XML or HTML. It allows you to write HTML elements and components in a JavaScript file, making it easier to describe the UI in React.

4. **How does React handle data binding?**
   - React uses one-way data binding, which means the flow of data is unidirectional. Changes in the parent components flow down to child components through props, ensuring a predictable data flow.

5. **What is a component in React?**
   - A component is a reusable and self-contained piece of UI that can be composed together to build complex user interfaces. Components can be either functional or class-based.

6. **Explain the state in React.**
   - State is a JavaScript object that stores the mutable data of a component. When the state of a component changes, React re-renders the component, reflecting the updated data in the user interface.

7. **What is the difference between state and props?**
   - Props (short for properties) are used to pass data from a parent component to a child component, whereas state is used to manage internal data and state changes within a component.
     
8. **What is the significance of React hooks, and can you name a few commonly used hooks?**
   * React hooks are functions that enable functional components to use state and lifecycle features. Some commonly used hooks include:
      - `useState` for managing state in functional components.
      - `useEffect` for handling side effects in functional components.
      - `useContext` for consuming React context in functional components.
      - `useReducer` for more complex state logic.
      - `useCallback` and `useMemo` for performance optimizations.

9. **What is the significance of the `useState` hook in React?**
   - `useState` is a hook in React that allows functional components to manage state. It returns an array with two elements: the current state value and a function to update it.

10. **What is the purpose of the `useEffect` hook?**
    - The `useEffect` hook is used to perform side effects in functional components, such as data fetching, subscriptions, or manually changing the DOM. It runs after every render.

12. **What is the React Router used for?**
    - React Router is a library for handling navigation in a React application. It enables the creation of single-page applications with dynamic, client-side routing.

13. **Explain the concept of lifting state up in React.**
    - Lifting state up refers to the practice of moving the state from a child component to a common ancestor (usually a parent) when multiple components need access to and share the same state.

14. **What is the purpose of keys in React lists?**
    - Keys are used to uniquely identify elements in a React list. They help React efficiently update and re-render components when the order or structure of the list changes.

15. **Explain the concept of controlled and uncontrolled components in React forms.**
    - Controlled components are React components whose form elements (like input fields) are controlled by React state, while uncontrolled components rely on the DOM for state management.

16. **How does React handle events?**
    - React uses a synthetic event system that normalizes browser inconsistencies and provides a consistent interface for handling events. Events in React are camel-cased and passed as functions.

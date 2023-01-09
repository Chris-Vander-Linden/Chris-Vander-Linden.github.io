[Back to Reading Notes](./README.md)

---

# Class 2: State and Props

## This topic matters as it relates to what I am studying in this module because...

State and props is how React knows which components to re-render. 

## React lifecycle

- Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?

> The render phase.

- What is the very first thing to happen in the lifecycle of React?

> Mounting.

- Put the following things in the order that they happen:

> constructor, render, componentDidMount, React Updates, componentWillUnmount.

- What does componentDidMount do?

> componentDidMount is used for events that happen outside of the component, such as making API calls.  I think it is similar to the "useEffect" hook in function components.

## React State Vs Props

- What types of things can you pass in the props?

> Arguments you want to pass, such as the initial count or data you want to have displayed, such as a title.

- What is the big difference between props and state?

> Props are handled outside of component while state is handled inside and manages/updates the data.

- When do we re-render our application?

> When the state changes, the component re-renders.

- What are some examples of things that we could store in state?

> All types of data.  You might update a count, an updated string, or maybe a light/dark theme boolean.

## Things I want to know more about

I want to learn more about the lifecycle.  It's still difficult for me to visualize it without seeing an actual example.

## Links to reading material

[React Docs - State and Lifecycle](https://reactjs.org/docs/state-and-lifecycle.html)

[React Docs - handling events](https://reactjs.org/docs/handling-events.html)

[React Tutorial through ‘Developer Tools’](https://reactjs.org/tutorial/tutorial.html)

[React Bootstrap Documentation](https://react-bootstrap.github.io/)

[Bootstrap Cheatsheet](https://getbootstrap.com/docs/5.0/examples/cheatsheet/)

[Bootstrap Shuffle - a class “sandbox”](https://bootstrapshuffle.com/classes)

[Netlify](https://www.netlify.com/)

[React State Vs Props](https://www.youtube.com/watch?v=IYvD9oBCuJI)

[Component Lifecycle Events](https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093)

---

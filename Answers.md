# Answers

- [ ] What is React JS and what problems does it try and solve? Support your answer with concepts introduced in class and from your personal research on the web.

React JS is a library created by Facebook to solve real world problems. It facilitates scalability, reusable DRY code, speedy development. Modularity, flexibility, abstraction. Modularity means functions can be broken down into independent building blocks. Flexibility so that those functions can easily be modified in the future. Abstraction emphasizes the big picture, not the nuts and bolts gritty details.

- [ ] What does it mean to _think_ in react?

To think in react means thinking of the big picture as you build your app. Think it through, plan ahead. Create a mockup, and then visualize or conceptualize how it can be broken down into components. Build a static UI, define state, add in interactivity. How do all of these individual pieces and processes work together, is everything fully broken down and defined properly so we're not repeating ourselves? How does this puzzle fit together.

- [ ] Describe state.

State holds information about a component. It is created inside the component, and it is dynamic so it can be changed (unlike props which can not be changed). Data can be hardcoded into state, or passed to it from props. State then monitors this data until the next render.

- [ ] Describe props.

Props, or properties, are passed into the component. They can be thought of as function calls or passing an argument to a function. 

- [ ] What are side effects, and how do you sync effects in a React component to state or prop changes?

A side effect is anything that affects something outside the scope of the function being executed, such as an API call. A side effect is something that can cause a component to return a different output for the same state and props. You can sync effects in a React component by using the useEffect hook.
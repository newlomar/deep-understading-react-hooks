# To start the application

```
npm start
```

## Below I will note some stuff to help me remember and understand hooks

Hooks General Rules

- Only call Hooks **at the top level**. Don't call Hooks inside loops, conditions, or nested functions.
- Only call Hooks **from React function components**. Don't call Hooks from regular JavaScript functions.

useEffect

- Used adds the ability to perfom side effects from a function component
- By default, React runs the effects after every render (including the first render)

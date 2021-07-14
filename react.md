# [React!](https://reactjs.org/docs/getting-started.html)
#### A JavaScript library for building user interfaces.

> Normally you would use JavaScript to select elements to change using events, while React is declarative and uses HTML/XML-like JSX code to define what will be displayed.

---

## State

State is good for forms. (checkboxes, radios, etc.)

## Props

Props cannot be changed within a component, but when they are changed, they will rerender the component.

---

## Glossary

Controlled Component
: If you pass in `undefined` or `null` as the initial `value` of an input element using state and also pass in an `onChange` function, it changes from an uncontrolled component to a controlled component which then must be manually updated on every render. To avoid this, always set the inital state value of an input element to an empty string instead of `undefined` or `null`.

---

## Things to Look Up
- [useContext hook](https://reactjs.org/docs/hooks-reference.html#usecontext)
- [React.lazy](https://reactjs.org/docs/react-api.html#reactlazy) & [React.Suspense](https://reactjs.org/docs/react-api.html#reactsuspense)

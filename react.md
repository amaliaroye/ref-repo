# React
[React Docs](https://reactjs.org/docs/getting-started.html)

## Fragments



Fragments allow you to group a list of children without adding extra nodes to the DOM.
```jsx {highlight=[3-5]}
return (
	<React.Fragment>
		<ChildA />
		<ChildB />
		<ChildC />
	</React.Fragment>
)
```

```jsx
return (
	<>
		<td>Hello</td>
		<td>World</td>
	</>
)
```

## JSX

Props default to **true** when no value is passed.

```jsx
<Component autocomplete />
<Component autocomplete={true}>
```

---

## Things to Look into
[React.lazy](https://reactjs.org/docs/react-api.html#reactlazy)
[React.Suspense](https://reactjs.org/docs/react-api.html#reactsuspense)
[useContext](https://reactjs.org/docs/hooks-reference.html#usecontext)

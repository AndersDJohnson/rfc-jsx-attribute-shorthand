# jsx-attribute-shorthand
A proposal for JSX attribute shorthand syntax.

Similar to https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Object_initializer#New_notations_in_ECMAScript_2015

```jsx
const title = 'something'
const onClick = () => {}

<button onClick= title= />
```
instead of (already supported):
```jsx
<button onClick={onClick} title={title} />
```
or (also already supported):
```jsx
<button {...{onClick, title}} />
```

# jsx-attribute-shorthand
A proposal for JSX attribute shorthand syntax.

Similar to https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Object_initializer#New_notations_in_ECMAScript_2015

```jsx
const onClick = () => {}

<button onClick= />
```
instead of:
```jsx
<button onClick={onClick} />
```
or:
```jsx
<button {...{onClick}} />
```


## What is React? ##

React is a flexible JavaScript library for building user interfaces. It is a Front-End Library created at by Facebook. When using React you think in components. React has a good ecosystem working together with NPM and Node

## What is JSX? ##

JSX is a syntax extension to JavaScript. It may remind you of template language or HTML but it comes with full power of JavaScript

```js
const element = <h1>Hello, world!</h1>
```

Below is an example of declaring a **Variable** called **name** and using it inside a **JSX**. Such as **2+2** of **user.firstname**.

```js
const name = 'Josh Perez';
const element = <h1>Hello, {name}</h1>;

ReactDOM.render(
element,
document.getElementById('root')
);
```
You can put any JavaScript expressions inside the curly braces in JSX. Such as **2 + 2** or **user.firstname**.

You can also use if statements and for loops, assign variables and accept arguments.

```js
function getGreeting(user) {
  if (user) {
    return <h1>Hello, {formatName(user)}!</h1>;
  }
  return <h1>Hello, Stranger.</h1>;
}
```

## Attributes with JSX ##

You can use quotes to specify a string literals as attributes:
```js
const element = <div tabIndex="0"></div>;
```

Or you can also use curly braces to embed a JavaScript expression inside a attribute:

```js
const element = <img src={user.avatarUrl}></img>;
```

Don’t put quotes around curly braces when embedding a JavaScript expression in an attribute. You should either use quotes (for string values) or curly braces (for expressions), but not both in the same attribute.

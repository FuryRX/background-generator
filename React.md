
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
You can put any JavaScript expressions inside the curly braces in JSX. Such as 2 + 2 or user.firstname.


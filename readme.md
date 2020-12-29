## Question 1.Explain what elements will match each of the following CSS selectors:

`div , p`
`div p`
`div > p`
`div + p`
`div ~ p`

<details><summary><b>Answer</b></summary>

1. div, p - Selects all <div> elements and all <p> elements
2. div p - Selects all <p> elements that are anywhere inside a <div> element
3. div > p - Selects all <p> elements where the immediate parent is a <div> element
4. div + p - Selects all <p> elements that are placed immediately after a <div> element
5. div ~ p - Selects all <p> elements that are anywhere preceded by a <div> element

</details>


<!-- ## Question 1. What's the difference between `undefined` and `not defined` in JavaScript

<details><summary><b>Answer</b></summary>

In JavaScript if you try to use a variable that doesn't exist and has not been declared, then JavaScript will throw an error `var name is not defined` and the script will stop executing thereafter. But If you use `typeof undeclared_variable` then it will return `undefined`.

Before starting further discussion let's understand the difference between declaration and definition.

`var x` is a declaration because we are not defining what value it holds yet, but we are declaring its existence and the need for memory allocation.

```javascript
var x; // declaring x
console.log(x); // output: undefined
```

`var x = 1` is both declaration and definition, here declaration and assignment of value happen inline for variable x—what we are doing is called "initialisation". In JavaScript both variable declarations and function declarations go to the top of the scope in which they are declared, then assignment happens—this series of events is called "hoisting".

A variable can be declared but not defined. When we try to access it, It will result `undefined`.

```javascript
var x; // Declaration
typeof x === 'undefined'; // Will return true
```

A variable can be neither declared nor defined. When we try to reference such variable then the result will be `not defined`.

```javascript
console.log(y);  // Output: ReferenceError: y is not defined
```

### Ref Link:
[http://stackoverflow.com/questions/20822022/javascript-variable-definition-declaration](http://stackoverflow.com/questions/20822022/javascript-variable-definition-declaration)

</details> -->
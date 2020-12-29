## Question 1.Explain what elements will match each of the following CSS selectors:

1. `div , p`
2. `div p`
3. `div > p`
4. `div + p`
5. `div ~ p`

<details><summary><b>Answer</b></summary>

1. div, p - Selects all `<div>` elements and all `<p>` elements
2. div p - Selects all `<p>` elements that are anywhere inside a `<div>` element
3. div > p - Selects all `<p>` elements where the immediate parent is a `<div>` element
4. div + p - Selects all `<p>` elements that are placed immediately after a `<div>` element
5. div ~ p - Selects all `<p>` elements that are anywhere preceded by a `<div>` element

</details>

## In CSS3, how would you select:

1. Every `<a>` element whose href attribute value begins with `https`.
2. Every `<a>` element whose href attribute value ends with `.pdf`.
3. Every `<a>` element whose href attribute value contains the substring `css`.

<details><summary><b>Answer</b></summary>

1. a[href^="https"]

2. a[href$=".pdf"]
 
3. a[href*="css"]

</details>
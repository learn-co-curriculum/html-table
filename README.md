# HTML Tables

## Overview

In this quick reading lesson we will learn about making tables in HTML.

## What's Covered in This Lesson

1. HTML table element

## Tables

Let's say you are building a web site to feature dessert recipes and you wish to insert a table of related data about each dessert such as name, level of difficulty, calories, etc. Using an HTML table will come in handy.

```html
<table>...</table>
```

We start off with the `<table>` element. Then we fill it with rows using `<tr>` elements each sets of these makes one row.

```html
<table>
  <tr>...</tr>
  <tr>...</tr>
  <tr>...</tr>
  <tr>...</tr>
</table>
```

The code above would create a table with four rows. Next to create some columns within each row, we can insert `<th>` to create header cells, and `<td>` to create normal cells.

```html
<table>
  <tr>
    <th> Recipe </th>
    <th> Calories Per Serving </th>
    <th> Difficulty </th>
  </tr>
  <tr>
    <td> Chocolate Lava Cake </td>
    <td> 475 </td>
    <td> Hard </td>
  </tr>
  <tr>
    <td> Crêpe Suzette </td>
    <td> 380 </td>
    <td> Medium </td>
  </tr>
  <tr>
    <td> Banana Split </td>
    <td> 724 </td>
    <td> Easy </td>
  </tr>
</table>
```

Below we can see the table that is created from this code. We also added a black border so you can see the edges of the table easily.

<table style="border-collpase: collapse; border: 1px solid black;">
  <tr>
    <th> Recipe </th>
    <th> Calories Per Serving </th>
    <th> Difficulty </th>
  </tr>
  <tr>
    <td>  Chocolate Lava Cake  </td>
    <td>  475  </td>
    <td> Hard </td>
  </tr>
  <tr>
    <td>  Crêpe Suzette  </td>
    <td>  380  </td>
    <td> Medium </td>
  </tr>
  <tr>
    <td>  Banana Split  </td>
    <td>  724  </td>
    <td> Easy </td>
  </tr>
</table>

## Summary

- HTML tables can be defined as `<table><tr><td>...</td></tr></table>`.
- We can define rows inside of tables as `<tr>` and cells inside of rows as either `<th>` header cell or `<td>` normal cells.

## Resources

- [Mozilla Dev Network - Learn HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [HTML Element Lookup Reference](https://developer.mozilla.org/en-US/docs/Web/HTML/Element)
- [HTML Element Cheatsheet](http://overapi.com/html-dom/)
- [Mozilla Developer Network - <table>](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/table)

# HTML Tables

## Overview

In this quick reading lesson we will learn about making tables in HTML.

## What's Covered in This Lesson 

1. HTML Table element

## Tables

Let's say you are building a web site to feature dessert recipes and yopu wish to insert a table of related data about each desert such as name, level of difficulty, calories, etc. Here using an HTML table will come in handy.

```html
<table>...</table>
```

We start off with the `<table>` element. Then we fill it with rows using `<tr>` elements each sets of these makes one row.

```html
<table>
  <tr>...</tr>
  <tr>...<tr>
  <tr>...</tr>
</table>
```

The code above would create a table with three rows. next to create some columns we can insert `<th>` to create header cells, and `<td>` to create normal cells.

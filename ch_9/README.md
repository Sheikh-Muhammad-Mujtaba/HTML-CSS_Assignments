# Chapter 9: Periodic Table style Example

In this we continue our example of the Periodic Table, but now we will use the **CSS** to add some style to it.
like back ground color alignment etc.

## Features Covered

### 3. Color-Coding Elements

- Elements are categorized by background colors using CSS classes, providing a visual distinction between different groups (e.g., metals, nonmetals, noble gases).

## CSS Styles Example

```css

h1,
h2 {
  text-align: center;
}

table {
  border: 2px solid black;
  border-collapse: separate;
  margin: auto;
  width: 90%;
}

tr {
  border-spacing: 2px;
  margin: auto;
  width: 90%;
}

td {
  border: 2px solid #000000;
  width: 50px;
  height: 50px;
  text-align: center;
  vertical-align: middle;
}

.bg-red {
  background-color: red;
}

.bg-purple {
  background-color: rgb(245, 50, 245);
}
.bg-dkblue {
  background-color: rgb(125, 25, 255);
}
.bg-yellow {
  background-color: rgb(255, 255, 0);
}
.bg-green {
  background-color: rgb(4, 87, 4);
}
.bg-brown {
  background-color: rgb(133, 67, 1);
}
.bg-peach {
  background-color: rgb(255, 190, 173);
}
.bg-gdbrown {
  background-color: #be902b;
}
.bg-blue {
  background-color: rgb(37, 112, 252);
}

.bg-lgpink {
  background-color: rgb(255, 168, 255);
}
```

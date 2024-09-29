# Periodic Table Example

This HTML page showcases a **Periodic Table** using various HTML and CSS techniques to display the elements in a visually appealing manner. The project illustrates how to effectively use HTML to create a structured representation of the periodic table.

## Features Covered

### 1. Header

- Demonstrates the use of `<h1>` and `<h2>` tags to display the main title and a brief description of the periodic table.

### 2. Periodic Table Structure

- **Table Tag (`<table>`)**: Utilized to create the grid layout for the periodic table.
- **Table Row (`<tr>`)**: Used to define rows in the table for each period of elements.
- **Table Data (`<td>`)**: Represents individual cells for each element, containing the atomic number, symbol, and name.

### 3. Color-Coding Elements

- Elements are categorized by background colors using CSS classes, providing a visual distinction between different groups (e.g., metals, nonmetals, noble gases).

### Example Structure:

```html
<h1>Periodic Table</h1>
<h2>A Comprehensive Representation of Chemical Elements</h2>

<table>
  <tr>
    <td class="alkali-metal">1<br /><strong>H</strong><br />Hydrogen</td>
    <td class="alkaline-earth-metal">2<br /><strong>He</strong><br />Helium</td>
    <!-- More elements -->
  </tr>
  <tr>
    <td class="alkali-metal">3<br /><strong>Li</strong><br />Lithium</td>
    <td class="alkaline-earth-metal">
      4<br /><strong>Be</strong><br />Beryllium
    </td>
    <!-- More elements -->
  </tr>
  <!-- Additional rows -->
</table>
```

## CSS Styles Example

```css
body {
  color: #333;
  background-color: #f0f0f0;
}

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
```

## Key HTML Tags Used

- **`<h1>`**: Represents the main title of the periodic table.
- **`<h2>`**: Provides a subtitle for additional context.
- **`<table>`**: Used to create a structured grid for displaying elements.
- **`<tr>`**: Defines a row in the periodic table.
- **`<td>`**: Represents a cell for each element, containing its atomic number, symbol, and name.
- **CSS Classes**: Utilized for color-coding elements based on their categories (e.g., metals, nonmetals).

# Chapter 3 Lists - Smartphone Ranking Example

This HTML page showcases the usage of various list-related HTML tags, including ordered lists (`<ol>`), description lists (`<dl>`), and unordered lists (`<ul>`), with a focus on creating a smartphone ranking display. This assignment demonstrates how to effectively structure and style lists in HTML.

## Features Covered

### 1. Ordered List
- Demonstrates the use of the `<ol>` tag to display an ordered list of items. In this case, the list represents the top 3 smartphone brands.

### 2. Description List
- **Description Term (`<dt>`)**: Used to represent the smartphone brand names.
- **Description Details (`<dd>`)**: Used to list the models under each brand, formatted as a nested unordered list.

### 3. Unordered List
- The `<ul>` tag is used inside the description details to list the smartphone models for each brand without implying any specific order.

### 4. Nested Lists
- Demonstrates how to nest an unordered list (`<ul>`) within a description list (`<dl>`) to provide additional details (models) for each brand.

### Example Structure:

```html
<ol>
  <dl>
    <li>
      <dt>Brand Name</dt>
      <dd>
        <ul>
          <li>Model 1</li>
          <li>Model 2</li>
          <li>Model 3</li>
        </ul>
      </dd>
    </li>
  </dl>
</ol>
```

## Key HTML Tags Used

- **`<ol>`**: Creates an ordered list of the top smartphone brands.
- **`<dl>`**: Represents a description list containing smartphone brand names and their models.
- **`<ul>`**: Creates an unordered list of models under each brand.
- **`<li>`**: List item tags inside both the ordered and unordered lists.
- **`<dt>`**: Defines a term in the description list (brand name).
- **`<dd>`**: Contains the definition or details (models) for the description term.

## Example Output

```
Top 3 Smartphones:
1. Samsung
    - Samsung Galaxy S10 Plus
    - Samsung Galaxy S9
    - Samsung Galaxy J5
2. Huawei
    - Huawei P30 Pro
    - Huawei Mate 20 Pro
    - Huawei P30
3. Apple
    - iPhone 11
    - iPhone XR
    - iPhone 11 Pro
```

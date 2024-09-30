# Chapter 7 - Forms

This assignment demonstrates the creation of a basic HTML form using the `<form>` tag. It includes essential form elements such as text inputs, email inputs, select dropdowns, radio buttons, checkboxes, and a submit button. This chapter introduces forms to beginners, covering how to collect and submit user data through an HTML form.

## Features Covered

### 1. HTML Structure
- **HTML Document Structure**: 
  - The document starts with the `<!DOCTYPE html>` declaration to define the HTML5 document type.
  - It includes a `<head>` section for the title and metadata.
  - The content, including the form, is placed inside the `<body>` section.

### 2. Forms
- **Form Tag**: The `<form>` tag is used to create a form that collects and submits user input.
  - The `action` attribute is set to `#`, indicating the form will not submit to an external source.
  - The `method` attribute is set to `post`, indicating the form data will be submitted using the POST method.

### 3. Form Fields
- **User Details Section**:
  - **Name Field**: The `<input type="text" />` element is used to create a text input field for the user's name, with the `required` attribute ensuring it must be filled out.
  - **Email Field**: The `<input type="email" />` element is used for entering an email, also with the `required` attribute.
  
- **User Review Section**:
  - **Select Dropdown**: The `<select>` element provides options for how the user heard about the service, with `<option>` elements inside.
  - **Radio Buttons**: The `<input type="radio" />` element allows the user to select an option indicating whether they would visit again.
  - **Textarea**: The `<textarea>` element is used for entering comments, with adjustable rows for customization.
  - **Checkbox**: The `<input type="checkbox" />` element allows the user to sign up for email updates.

### 4. Submit Button
- The form contains a submit button (`<input type="submit" />`) to send the data for processing.

### 5. Explanation of Tags
- The form uses fundamental tags such as `<fieldset>`, `<legend>`, `<label>`, and input elements (`<input>`, `<textarea>`, and `<select>`) to create a structured and user-friendly form.

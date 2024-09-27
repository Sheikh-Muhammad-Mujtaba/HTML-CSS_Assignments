# **Chapter 4:-**  HTML Linking Example

## Overview

This project demonstrates the usage of various types of links in HTML. In the provided HTML file, we create links to external websites, internal sections of the same page, and an external `about.html` page. The file also uses an email link to allow users to contact via email.

## Table of Contents

- [**Chapter 4:-**  HTML Linking Example](#chapter-4---html-linking-example)
  - [Overview](#overview)
  - [Table of Contents](#table-of-contents)
  - [Introduction](#introduction)
  - [Types of Links Used](#types-of-links-used)
    - [1. External Links](#1-external-links)
    - [2. Internal Links (Anchors)](#2-internal-links-anchors)
    - [3. Internal Page Links](#3-internal-page-links)
    - [4. Email Links](#4-email-links)
  - [Code Structure](#code-structure)
  - [Conclusion](#conclusion)

## Introduction

In HTML, links (or anchors) are created using the `<a>` tag. The `href` attribute inside this tag specifies the destination of the link. In this example, we demonstrate different types of links: external links to other websites, internal links that link to sections within the same page, and a link to a separate page.

## Types of Links Used

### 1. External Links

External links navigate to other websites. In our code, we have created links to specific Wikipedia pages that provide information about holidays and observances in Pakistan.

**Example:**

```html
<a href="https://en.wikipedia.org/wiki/New_Year%27s_Day">New Year's Day in Pakistan</a>
```

### 2. Internal Links (Anchors)

Internal links navigate to different sections within the same HTML page. They are often used for "back to top" functionality, as seen in our code.

**Example:**

```html
<a href="#top">🔝</a>
```

In this case, clicking this link will scroll the page back to the top where the element with `id="top"` is located.

### 3. Internal Page Links

Internal page links navigate between pages of the same website or directory. In this example, the link goes to an `about.html` page which contains additional information about calendar highlights.

**Example:**

```html
<a href="about.html">About Calendar highlights</a>
```

Ensure that the `about.html` file exists in the same directory as this file.

### 4. Email Links

Email links allow users to send an email by clicking on the link. The `mailto:` scheme is used in the `href` attribute to enable this feature.

**Example:**

```html
<a href="mailto:info@example.com">contact us</a>
```

When clicked, the user's default email client will open, and they can send an email to the specified address.

## Code Structure

- We start with a title and header tags (`<h1>`, `<h2>`, `<h3>`) to structure the content.
- The `<a>` tags are used to create links for external websites, internal sections (anchors), an internal page, and email functionality.
- The `href` attribute in the `<a>` tag defines the link target.
- We use anchors (`id="top"`) to mark the top of the page for easy navigation back to the beginning.

## Conclusion

This HTML document demonstrates how to use different types of links in web development. Understanding how to create internal and external links, as well as email links, is fundamental when building web pages. This example shows how simple it is to implement these features in your own HTML projects.

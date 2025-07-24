# Essential HTML & CSS Cheatsheet

## HTML Structure Basics

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Page Title</title>
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <!-- Your content goes here -->
  </body>
</html>
```

## Essential HTML Tags

### Text & Content

```html
<h1>Main Heading</h1>
<!-- Biggest heading -->
<h2>Subheading</h2>
<!-- Smaller headings: h3, h4, h5, h6 -->
<p>This is a paragraph</p>
<!-- Regular text -->
<span>Inline text</span>
<!-- For styling parts of text -->
<br />
<!-- Line break -->
<strong>Bold text</strong>
<!-- Important/bold text -->
<em>Italic text</em>
<!-- Emphasized/italic text -->
```

### Lists

```html
<ul>
  <!-- Unordered list (bullets) -->
  <li>Item 1</li>
  <li>Item 2</li>
</ul>

<ol>
  <!-- Ordered list (numbers) -->
  <li>First item</li>
  <li>Second item</li>
</ol>
```

### Links & Images

```html
<a href="https://example.com">Link text</a>
<a href="page.html">Internal link</a>
<img src="image.jpg" alt="Description" />
```

### Layout Containers

```html
<div>Block container</div>
<!-- Generic block element -->
<header>Page/section header</header>
<nav>Navigation menu</nav>
<main>Main content area</main>
<section>Content section</section>
<footer>Page footer</footer>
```

### Forms (Basics)

```html
<form>
  <input type="text" placeholder="Enter text" />
  <input type="email" placeholder="Email" />
  <input type="password" placeholder="Password" />
  <button type="submit">Submit</button>
</form>
```

## Essential CSS Properties

### Text Styling

```css
color: blue; /* Text color */
font-size: 16px; /* Text size */
font-weight: bold; /* Text thickness: normal, bold */
text-align: center; /* left, center, right */
text-decoration: underline; /* none, underline */
```

### Background & Colors

```css
background-color: #f0f0f0; /* Background color */
background-image: url("image.jpg");
background-size: cover; /* cover, contain */
```

### Box Model (Spacing)

```css
margin: 10px; /* Space outside element */
margin-top: 20px; /* Individual sides: top, right, bottom, left */
padding: 15px; /* Space inside element */
border: 2px solid black; /* Border: width style color */
width: 200px; /* Element width */
height: 100px; /* Element height */
```

### Display & Layout

```css
display: block; /* block, inline, inline-block, none, flex */
position: relative; /* static, relative, absolute, fixed */
top: 10px; /* Position from top */
left: 20px; /* Position from left */
```

### Flexbox (Modern Layout)

```css
/* On parent container */
display: flex;
justify-content: center; /* left-right: flex-start, center, flex-end, space-between */
align-items: center; /* up-down: flex-start, center, flex-end */
flex-direction: row; /* row, column */

/* On child elements */
flex: 1; /* Takes available space */
```

## CSS Selectors (How to Target Elements)

```css
/* Tag selector */
p {
  color: red;
}

/* Class selector (use class="my-class" in HTML) */
.my-class {
  font-size: 18px;
}

/* ID selector (use id="my-id" in HTML) */
#my-id {
  background-color: yellow;
}

/* Multiple elements */
h1,
h2,
h3 {
  color: blue;
}

/* Element inside another */
div p {
  margin: 10px;
}
```

## Quick Color Reference

```css
/* Named colors */
color: red, blue, green, black, white, gray;

/* Hex colors */
color: #ff0000; /* Red */
color: #00ff00; /* Green */
color: #0000ff; /* Blue */
color: #000000; /* Black */
color: #ffffff; /* White */

/* RGB colors */
color: rgb(255, 0, 0); /* Red */
color: rgba(255, 0, 0, 0.5); /* Red with 50% transparency */
```

## Sample Mini Project Structure

**index.html**

```html
<!DOCTYPE html>
<html>
  <head>
    <title>My First Website</title>
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <header>
      <h1>Welcome to My Site</h1>
      <nav>
        <a href="#about">About</a>
        <a href="#contact">Contact</a>
      </nav>
    </header>

    <main>
      <section id="about">
        <h2>About Me</h2>
        <p>This is my first website!</p>
      </section>
    </main>

    <footer>
      <p>&copy; 2024 My Website</p>
    </footer>
  </body>
</html>
```

**style.css**

```css
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 20px;
  background-color: #f5f5f5;
}

header {
  background-color: #333;
  color: white;
  padding: 20px;
  text-align: center;
}

nav a {
  color: white;
  text-decoration: none;
  margin: 0 15px;
}

main {
  max-width: 800px;
  margin: 20px auto;
  background-color: white;
  padding: 20px;
}

footer {
  text-align: center;
  margin-top: 40px;
  color: #666;
}
```

## Pro Tips for Learning

1. **Start simple**: Create a basic page with just headings and paragraphs
2. **Experiment constantly**: Change colors, sizes, and spacing to see what happens
3. **Use browser dev tools**: Right-click → "Inspect Element" to see and modify CSS live
4. **One thing at a time**: Master basic layouts before learning advanced features
5. **Practice projects**: Build a personal page, recipe site, or hobby page

This cheatsheet covers 90% of what you'll use daily. Start building and add new properties as you need them!


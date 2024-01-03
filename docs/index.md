# Getting Started

## Installation

To begin exploring your site template, follow these steps:

- Open the `template` folder to access all necessary files.

- Upload these files to your Web Server to utilize the template.

Ensure you upload all the required files listed below:

- `template/assets/css`: CSS Folder

- `template/assets/css/style.css`: Main Stylesheet

- `template/assets/js`: Javascript Folder

- `template/assets/js/script.js`: Main Javascript file

- `template/assets/images`: Image Folder

- `template/assets/resume`: Resume Folder

- `template/index.html`: Index File/Homepage

---

## Initial Setup

Before editing your site template, set up these features:

### Changing Fonts

#### Using API

You can integrate Google Fonts API by adding a stylesheet link to request desired web font(s) within each page's head tags.

**_Code Example_**

```html
<link
  href="https://fonts.googleapis.com/css2?family=Syne:wght@400;600;700;800&display=swap"
  rel="stylesheet"
/>
```

To style an element with the requested web font in a stylesheet:

**_Code Example_**

```css
html,
body {
  font-family: "Poppins", sans-serif;
}
```

#### Self Hosted

For self-hosted fonts, use the following code at the beginning of the style.css file.

**_Code Example_**

```css
@font-face {
  font-family: "MyWebFont";
  src: url("fonts/webfont.woff2") format("woff2"), url("fonts/webfont.woff")
      format("woff"), url("fonts/webfont.ttf") format("truetype"), url("fonts/webfont.svg#svgFontName")
      format("svg");
}
```

Place the font files inside the `fonts` folder in the template's **_Root Folder_**.

---

### Page Color Scheme

To modify the colors used in the page:

- Open the `style.css` file.

- Inside the `:root` section, locate the colors area.

- Adjust the variable names and the colors used throughout the stylesheet.

**_Note:_** The variable name must be change throughout the whole stylesheet.

---

### Changing Images

To change images on the page:

- Navigate to the `assets/images` folder.

- Replace the existing images with your relevant images.

### Changing Resume

To add your resume to your website:

- Visit the `assets/resume` folder.

- Replace the existing `resume.pdf` file with your updated resume.

## Custom JavaScript Code

You have the flexibility to insert your custom JavaScript code within the `assets/script.js` file.

**_Code Example:_**

```javascript
function functionName() {
  // Add your custom JavaScript code here
}
```

This framework permits you to define and incorporate your unique JavaScript functions or modifications into the specified `assets/script.js` file for convenient organization and implementation of your custom code.

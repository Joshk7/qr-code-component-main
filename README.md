# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

-   [Overview](#overview)
    -   [Screenshot](#screenshot)
    -   [Links](#links)
-   [My process](#my-process)
    -   [Built with](#built-with)
    -   [What I learned](#what-i-learned)
    -   [Continued development](#continued-development)
    -   [Useful resources](#useful-resources)
-   [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

This is my solution to the QR Code Component on FrontEnd Mentor.

### Screenshot

![](./screenshot.png)

### Links

-   Solution URL: [GitHub repository](https://github.com/Joshk7/qr-code-component-main)
-   Live Site URL: [Live Site using vercel](https://qr-code-component-main-six-sable.vercel.app)

## My process

### Built with

-   Semantic HTML5 markup
-   CSS custom properties
-   Flexbox

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

I brushed up my css layout styles for the attribution by wrapping it in an html footer tag and then setting fixed positioning with css:

```html
<footer>
    <div class="attribution">
        ...
    </div>
</footer>
```

```css
footer {
    position: fixed;
    ...
}
```

Additionally, setting the body element to display: flex allowed me to easily center the main qr-code content.

```css
body {
	display: flex;
	justify-content: center;
	align-items: center;
    ...
}
```

### Continued development

I could improve this project further having links change color whenever the user hovers over them with their mouse.
The project also needs elements for accessibility to be complete.

### Useful resources

-   [position - CSS MDN Webdocs](https://developer.mozilla.org/en-US/docs/Web/CSS/position) - This helped me review fixed positioning and how it behaves in the project.

## Author

-   Website - [Josh Kahlbaugh](https://joshuakahlbaugh.pages.dev/)
-   Frontend Mentor - [@Joshk7](https://www.frontendmentor.io/profile/Joshk7)

**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**

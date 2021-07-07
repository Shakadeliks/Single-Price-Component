# Frontend Mentor - Single price grid component solution

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See a hover state on desktop for the Sign Up call-to-action

### Links

- Solution URL: https://github.com/Shakadeliks/Single-Price-Component
- Live Site URL: https://shakadeliks.github.io/Single-Price-Component/

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

The assignment was my first experience with responsive design and a mobile fit approach to development.
Tying in with this was my first use of media queries and dealing with viewport sizes.

Building this project exposed me to CSS grid and it's mechanics. Grid provided a solution to the layout that was needed for the
component's design.

I now am comfortable with setting up CSS custom properties and implementing those variables within my code.

Lastly, I was able to become more familiar with the use of semantic tags to improve the structure and readibility of my HTML.

```html
<section id="top-section">
  <article id="top-article">
    <h1>Join our community</h1>

    <p class="b-yellow">30-day, hassle-free money back guarantee</p>

    <p id="top-info-pg">
      Gain access to our full library of tutorials along with expert code
      reviews.<br />
      Perfect for any developers who are serious about honing their skills.
    </p>
  </article>
</section>
```

```css
@media only screen and (min-width: 63.5em) {

    main {

        display: grid;
        grid-template-columns: auto auto;
        grid-template-rows: auto auto;
        grid-template-areas: "top top"
                            "bottom-left bottom-right";
        border-radius: 0.5rem;

    }

    #top-section {
        padding: var(--desktopPaddingY) var(--desktopPaddingX);

    }

    #bottom-left-section {
        padding: var(--desktopPaddingY) var(--desktopPaddingX);
    }

    #bottom-right-section {
        padding: var(--desktopPaddingY) var(--desktopPaddingX);
    }
```

### Continued development

I would like to further improve on this project by figuring out methods of writing cleaner, less dense CSS.
This can make the CSS easier to read and customise. I would also like to improve my use of semantic HTML tags to be
more inline with standard practices.

### Useful resources

- [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference) - This helped me with any documentation that I needed to achieve the CSS styles and help me understand the styling concepts I needed for this project.

- [W3schools](https://www.w3schools.com/css/css_rwd_grid.asp) - This article was crucial with helping me understand the CSS grid and how to use it fo this design.

## Author

- Website - [Olwethu "Shak" Matiwana](https://www.your-site.com)
- Frontend Mentor - [@Shakadeliks](https://www.frontendmentor.io/profile/Shakadeliks)

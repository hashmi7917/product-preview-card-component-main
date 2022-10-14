# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

Large Screen
![Screenshot 2022-10-14 at 3 27 57 PM](https://user-images.githubusercontent.com/38833326/195820008-4db51670-5909-4e9f-b100-8ed0a160df5b.png)

Mobile Screen
<br/>
![Screenshot 2022-10-14 at 3 29 16 PM](https://user-images.githubusercontent.com/38833326/195820186-74746688-0327-4c69-aff3-18fbaad532ad.png)

### Links

- Solution URL: [Add solution URL here](https://github.com/hashmi7917/product-preview-card-component-main)
- Live Site URL: [Add live site URL here](https://hashmi7917.github.io/product-preview-card-component-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Google Custom Fonts
- Mobile-first workflow

### What I learned

FLexbox Layouts , CSS Custom Variable.

To see how you can add code snippets, see below:

```html
<main>
  <div class="container">
    <div class="content">
      <div class="content-image">
        <picture>
          <source
            media="(max-width:1400px)"
            srcset="./images/image-product-desktop.jpg"
          />
          <source
            media="(max-width:450px)"
            srcset="./images/image-product-mobile.jpg"
          />
          <img
            src="./images/image-product-desktop.jpg"
            alt="perfume bottle"
            style="width: 100%"
          />
        </picture>
      </div>
      <div class="content-info">
        <p>perfume</p>
        <h1>Gabrielle Essence Eau De Parfum</h1>
        <p>
          A floral. solar and voluptuous interpretation composed by Over Polge.
          Pertumer-Creator for the House of CHANEL
        </p>

        <h4>$149.99 <span>$169.99</span></h4>
        <button>
          <span
            ><img src="./images/icon-cart.svg" alt="add to cart button"
          /></span>
          Add to Cart
        </button>
      </div>
    </div>
  </div>
</main>
```

```css
:root {
  --dark-cyan: hsl(158, 36%, 37%);
  --cream: hsl(30, 38%, 92%);
  --very-dark-blue: hsl(212, 21%, 14%);
  --dark-greyish-blue: hsl(228, 12%, 48%);
  --white: hsl(0, 0%, 100%);
  --montserrat: "Montserrat", sans-serif;
  --fraunces: "Fraunces", serif;
}
```

```js

```

### Continued development

Html Semantic Markup, CSS Variables, CSS Layots, Flexbox.

### Useful resources

## Author

- Website - [Hashmi](https://hashmi7917.github.io/hashmiportfolio/)
- Frontend Mentor - [@hashmi7917](https://www.frontendmentor.io/profile/hashmi7917)
- Twitter - [@hash_m_ee](https://twitter.com/@hash_m_ee)

## Acknowledgments

Indipendtly Developed

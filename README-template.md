# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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
- See hover states for interactive elements

### Screenshot

#### Mobile view

![](./solution/Screenshot%202025-04-03%20at%2023-24-33%20Frontend%20Mentor%20NFT%20preview%20card%20component.png)

#### Desktop View

![](./solution/Screenshot%202025-04-03%20at%2023-24-57%20Frontend%20Mentor%20NFT%20preview%20card%20component.png)

#### hover view

![](./solution/Screenshot%202025-04-03%20232930.png)

### Links

- Solution URL: [NFT Preview Card Github repositor](https://github.com/Praveen-BE/NFT-Preview-Card)
- Live Site URL: [Add live site URL here]()

## My process

- i create html markup
- css reset from [JoshWComeau](https://www.joshwcomeau.com/css/custom-css-reset/?from=newsletter)
- I write css for Mobile First work
- then i try to adjust slightly responsive for desktop

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
<!-- - [React](https://reactjs.org/) - JS library
- [Next.js](https://nextjs.org/) - React framework
- [Styled Components](https://styled-components.com/) - For styles -->

### What I learned

- Double Layer of Box Shadow.

```css
.card {
  margin: auto;
  box-shadow: 0 10px 5px 20px var(--clr-neutral-900), 0px 20px 5px 40px var(--clr-neutral-900-tranperent);
}
```

- i struggle to implement when hover show icon and color, i get from [mendezpvi](https://github.com/mendezpvi/fem-nft-preview-card-component/blob/main/css/index.css) repository code he/she put link on Discord it really help lot otherwise i pull my hair whole day.

```css
.card__img {
  position: relative;
  display: grid;
  place-items: center;
  overflow: hidden;
  inline-size: 100%;
  margin: 0;
  border-radius: 0.5rem;
  overflow: hidden;
  cursor: pointer;
}

.card__img img {
  border-radius: 0.5rem;
  inline-size: 100%;
  block-size: auto;
}

.card__img:hover:after {
  content: url(./images/icon-view.svg);
  position: absolute;
  inset: 0;
  display: grid;
  place-items: center;
  background-color: hsl(from var(--clr-secondary-200) h s l/0.5);
}
```

## Author

- Frontend Mentor - [Praveen](https://www.frontendmentor.io/profile/Praveen-BE)

## Acknowledgments

- [Frontend Mentor](https://www.frontendmentor.io)
- [Kevin Powell](https://www.youtube.com/@KevinPowell)

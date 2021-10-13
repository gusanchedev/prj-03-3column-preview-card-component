# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](.design/Screenshot-3-column-preview-card-component.png)


### Links

- Solution URL: [Frontendmentor.io](https://your-solution-url.com)
- Live Site URL: [Vercel's live site URL here](https://prj-03-3column-preview-card-component.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS variables
- Flexbox
- Mobile-first workflow

### What I learned

I learned to structurate CSS from general to particular styles beginning from variables and global selectors like root, html and *.

```css
:root {
  --Bright-orange: hsl(31, 77%, 52%);
  --Dark-cyan: hsl(184, 100%, 22%);
  --Very-dark-cyan: hsl(179, 100%, 13%);
  --Transparent-white-paragraphs: hsla(0, 0%, 100%, 0.75);
  --Verylight-gray-background-headings-buttons: hsl(0, 0%, 95%);
}
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-size: 15px;
}

body {
  height: auto;
  display: flex;
  justify-content: center;
  align-items: center;
  font-family: "Lexend Deca", sans-serif;
  background-color: var(--Verylight-gray-background-headings-buttons);
}
```
Use of pseudo-classes: The :first-of-type CSS pseudo-class represents the first element of its type among a group of sibling elements.
```css
p:first-of-type {
  text-transform: uppercase;
  color: var(--Verylight-gray-background-headings-buttons);
  font-size: 30px;
  font-family: "Big Shoulders Display", cursive;
  margin: 30px 0 30px 0;
}
p:last-of-type {
  color: var(--Transparent-white-paragraphs);
  line-height: 25px;
  padding-right: 20px;
}
```
The :hover CSS pseudo-class matches when the user interacts with an element with a pointing device, but does not necessarily activate it. It is generally triggered when the user hovers over an element with the cursor (mouse pointer).
```css
.sedan-box button:hover {
  background-color: var(--Bright-orange);
  color: var(--Verylight-gray-background-headings-buttons);
}
```

### Continued development

In future challenges I plan to use Tailwindcss for styling and Vite as frontend development environmnt.

### Useful resources

- [First of type pseudo-class](https://developer.mozilla.org/en-US/docs/Web/CSS/:first-of-type) in order to reduce the amount of repeated code.
- [Hover pseudo-class](https://developer.mozilla.org/es/docs/Web/CSS/:hover) - Hover pseudo-class for active states.

## Author

- Website - [Gustavo Sanchez](https://www.gusanche.dev)
- Frontend Mentor - [@gusanchedev](https://www.frontendmentor.io/profile/gusanchedev)
- Github - [@gusanchedev](https://www.github.com/gusanchedev)
- Twitter - [@gusanchedev](https://www.twitter.com/gusanchedev)
- Linkedin - [gusanchedev](https://www.linkedin.com/in/gusanchedev/)

## Acknowledgments

Thanks to Mariapaz for being my friend and support 💙

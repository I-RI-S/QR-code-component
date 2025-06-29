# Frontend Mentor - QR code component solution

This is my solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). The goal of this challenge is to practice building a simple and responsive layout using only HTML and CSS.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

This project is a solution to the Frontend Mentor QR code component challenge. The goal was to build a responsive QR card using only HTML and CSS. The card includes an image, a title, and a short description, all styled to match the design provided in the Figma file.

### Screenshot

![QR Code Component Screenshot](./images/screenshot.png)

## My process

### How I approached it

I first analyzed the design file in Figma to understand the structure. I identified the main container, the image section, and the text section. Based on that, I created a semantic HTML layout and styled each part using custom CSS.

I used Flexbox to center the entire card on the page, followed by applying padding, border radius, and shadows to match the design as closely as possible. I also imported a Google Font ("Outfit") to replicate the typography used in the design.

### Built with

- Semantic HTML5
- CSS3
- Flexbox
- Mobile-first approach
- Google Fonts (Outfit)

### What I learned

While working on this project, I practiced using:

- **Flexbox** to center elements both vertically and horizontally:

```css
body {
  display: flex;
  justify-content: center;
  align-items: center;
  min-height: 100vh;
}

Custom styling for text and spacing

Google Fonts integration:
<link href="https://fonts.googleapis.com/css2?family=Outfit:wght@100..900&display=swap" rel="stylesheet">
```

## Author

Coded by I-RI-S.

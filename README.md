# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
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

### Screenshot

![Desktop screenshot](./images/screenshot-desktop.png)

### Links

- Live Site URL: [Add live site URL here](https://63bfbab782cf1e24b5d787f3--ubiquitous-jalebi-d22ebe.netlify.app/)

## My process

### Built with

- [Tailwind CSS](https://63bfbab782cf1e24b5d787f3--ubiquitous-jalebi-d22ebe.netlify.app/)
- Flexbox

### What I learned

I think the creator of this challenge used tailwind, as the `rem` padding values and default tailwind font sizes matched up perfectly to the screenshots provided.

Here is the bulk of the solution:

```html
<body class="bg-lightGray flex justify-center flex-col align-middle h-screen">
  <div class="text-center max-w-xs mx-auto bg-white rounded-2xl p-4 drop-shadow-xl">
    <img src="images/image-qr-code.png" class="rounded-xl" />
    <div class="p-3">
      <div class="text-xl font-extrabold text-darkBlue">
        Improve your front-end skills by building projects
        </div>
      <div class="mt-3 text-grayishBlue text-md">
        Scan the QR code to visit Frontend Mentor and take your coding skills to the next level
        </div>
    </div>
  </div>
```

### Continued development

I think it would have been nice to spend more time thinking outside the box on the design and what could be added, such as idle or hover animations. I would also like to ensure that the project is ADA compliant, even though it's not fun and I do enough of that at my day job.

## Author

- Website - [Spencer Baumruk (Linktree)](https://linktr.ee/spencerbaumruk)
- Frontend Mentor - [@sbaumruk](https://www.frontendmentor.io/profile/sbaumruk)
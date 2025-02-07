# Frontend Mentor - Social links profile solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- See hover and focus states for all interactive elements on the page

### Screenshot

![](/fullpage.png)
![](/mobile.png)

### Links

- Solution URL: [https://www.frontendmentor.io/solutions/semantic-html5-markup-font-size-using-clamp-flexbox-mobile-first-Jd_61pPAtA](https://www.frontendmentor.io/solutions/semantic-html5-markup-font-size-using-clamp-flexbox-mobile-first-Jd_61pPAtA)
- Live Site URL: [https://fadymas.github.io/social-links-profile-main/](https://fadymas.github.io/social-links-profile-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- Font-size using clamp()

### What I learned

I learned a great deal about image editing.

```css
section.social-buttons {
  height: calc(100% - 205px);
}

img {
  width: 230px;
  clip-path: circle(26%);
  object-fit: cover;
  object-position: top;
  height: 100px;
}
```

### Continued development

```css
p {
  font-size: clamp(calc(1.13rem - 3.5px), 1vw + 0.38rem, calc(1rem - 2.5px));
}
```

### Useful resources

- [https://developer.mozilla.org/en-US/](https://developer.mozilla.org/en-US/) - This website helped me achieve responsive font sizes.

## Author

- Github - [@fadymas](https://github.com/fadymas)
- Frontend Mentor - [@fadymas](https://www.frontendmentor.io/profile/fadymas)
- Linkedin - [@fadymas](https://www.linkedin.com/in/fadymas)

## Acknowledgments

I would like to extend my gratitude to [KonradJam](https://www.frontendmentor.io/profile/KonradJam) or helping me make the font size responsive in my design. Additionally, I appreciate the guidance on measuring spaces correctly in design without figma, which I will apply in future designs. Your assistance was truly invaluable!

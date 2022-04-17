# Frontend Mentor - Equalizer landing page solution

This is a solution to the [Equalizer landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/equalizer-landing-page-7VJ4gp3DE). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./screenshot.png)

### Links

- Solution URL: [link](https://www.frontendmentor.io/solutions/equalizer-landing-page-with-scss-HJy8Ok54q)
- Live Site URL: [link](https://miguelzaga.github.io/equalizer-landing-page/)

## My process

### Built with

- Semantic HTML5 markup
- Flexbox
- Mobile-first workflow
- SCSS

### What I learned
#### SCSS
This is my second project using SCSS, though, this time I guided myself with the [structure](https://css-irl.info/a-modern-front-end-workflow-part-3/) that Michelle Barker recommends. The use of partials and mixins is useful. At the beginning it was confusing, but when I got used to, it is way faster than what I was doing before.
```css
@import '01-config/functions';
@import '01-config/variables';
@import '01-config/mixins';

```

#### SVG files in HTML
I was placing the social media icons with an img tag. When I tried to add the hover effect I wasn't able. Then I started searching in the web about hover effects and stumbled upon the css tricks [article](https://css-tricks.com/using-svg/). I found out that is way easier to implement these effects with SVG files. It turns out that changing the fill property of a SVG is very convenient.
```html
<svg class="footer_facebook" ...> </svg>
<svg class="footer_instagram" ...> </svg>
<svg class="footer_twitter" ...> </svg>

```

### Continued development

#### Sass structures
I need to keep learning about sass structures. I read a little about the inverted pyramid and some bem alternatives. I think they could improve my worflow. At the beginning I was confused and it cost me to adapt to the structure that I used. I hope to get more comfortable and proficent.

#### HTML structure
I am not sure if I placed correctly the background images. I think I can learn better practices. Also, about containers and wrappers. I don't think I did a good job at organizing some divs. In some places I placed too many classes and could have separeted some divs and it would have been easier to work on them.

### Useful resources

- [Building Our Sass Architecture](https://css-irl.info/a-modern-front-end-workflow-part-3/) - This helped me to organize my Sass files.
- [Using SVG](https://css-tricks.com/using-svg/) - It helped me achieve the hover effect on the social icons.

## Author

- Frontend Mentor - [@miguelzaga](https://www.frontendmentor.io/profile/miguelzaga)
- Linkedin - [Miguel Zapata](https://www.linkedin.com/in/miguelzaga/)

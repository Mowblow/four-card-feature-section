# Frontend Mentor - Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![](./screenshot.jpg)

Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it.

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.

**Note: Delete this note and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties/variables
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```html
<h1>Some HTML code I'm proud of</h1>
```

```css
@media screen and (min-width: 1200px) {
  main {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    grid-template-rows: repeat (2, auto);
    column-gap: 2rem;
  }

  .card:nth-child(1) {
    transform: translateY(50%);
  }

  .card:nth-child(4) {
    transform: translateY(50%);
    grid-column: 3/4;
    grid-row: -1/-2;
  }

  .card:nth-child(3) {
    grid-column: 2/3;
  }
  .header__text {
    width: 100%;
  }
}
```

### Continued development

I want to learn more about CSS grids and practice using it more.
I also want to read more about specificity and the cascade, I believe we often overlook the importance of going over important concepts because of how easy it may seem. Trust me, it isn't..

### Useful resources

- [CSS grid layout ](https://css-tricks.com/snippets/css/complete-guide-grid/) - This helped me to understand more on positioning grid items using the grid-row and grid-column values.

## Author

- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/Mowblow)
- Twitter - [@yourusername](https://www.twitter.com/moblazer005)

## Acknowledgments

Everybody out there on the internet who has gone through one problem I face now or in the future. I thank you for your solutions.

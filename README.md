# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
- CSS custom properties
- Flexbox
- Atom

### What I learned

This is my first project using Flexbox.

```CSS codes I am proud of:-
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
.features>p {
  color: hsla(0, 0%, 100%, 0.6);
  font-size: 0.7rem;
}
.second-card {
  background: url("images/image-header-desktop.jpg");
  width: 100%;
  height: 100%;
  background: linear-gradient(hsl(277, 64%, 61%));
}

.second-card {
  background-image: url("images/image-header-desktop.jpg");
  display: block;
  position: relative;
}

.second-card::after {
  content: "";
  background: hsl(277, 64%, 61%);
  opacity: 0.4;
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  z-index: 1;
}
```


### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

1. Flexbox
2. CSS Styling Skills
3. HTML Structuring Skills So That I Can Structure A Website In Minutes😁.

### Useful resources

- [Stack Overflow] - This is for any query of coding in any field , if you are stuck somewhere.
- [W3 Schools] - This provides all important documentation regarding all of the tags, properties, methods etc. of HTML, CSS , and Javascript.

## Author

- Website - [Madhav Khandelwal](https://github.com/Sanskrit-acodinglanguage)
- Frontend Mentor - [@Sanskrit-acodinglanguage](https://www.frontendmentor.io/profile/Sanskrit-acodinglanguage)


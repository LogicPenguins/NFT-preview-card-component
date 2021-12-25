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

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

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

- HTML5
- SCSS (superset of css)


### What I learned

Below are some code snippets that I'm proud of, ranging from new user cases to figuring out how to do things I simply did not know were possible, such as centering with css transform

```html
<div class="credit">
  <img src="images/image-avatar.png" alt="">
  <span class="credit-text">
    Creation of <span class="credit-user">Jules Wyvern</span>
  </span>
</div>
```
```css
.main-image { 
  position: relative;
  padding-top: 20px;
  padding-left: 15px;
  padding-right: 20px;

  img {
      background-repeat: no-repeat;
      background-size: 320px;
      width: 320px;
      height: 320px;
      border-radius: 10px;
  }

  div {
      position: absolute;
      top: 15px;
      background-color: rgba(0, 255, 247, 0.476);
      width: 92%;
      height: 95%;
      z-index: 1;
      opacity: 0;
      transition: opacity 0.3s ease-in-out;

      img {
          position: absolute;
          left: 50%;
          top: 50%;
          width: 40px;
          height: auto;
          transform: translate(-50%, -50%)
      }
  }

  div:hover {
      cursor: pointer;
      opacity: 1;
  }
      
  }
}
```
## Author

- Website - [In-Progress]()
- Frontend Mentor - [@Logic](https://www.frontendmentor.io/profile/LogicPenguins)
- Twitter - [@Xmexy](https://twitter.com/Xmexyyy)

## Acknowledgments

Thank you to the guys over on the Programmer's Hangout Discord server for helping me out a bunch with this little project. First time doing a frontend mentor challenge
and can't say I would have been able to do it without them :)

Programmer's Hangout Discord: [Programmer's Hangout](https://discord.gg/programming)

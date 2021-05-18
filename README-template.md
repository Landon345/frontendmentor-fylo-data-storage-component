# Frontend Mentor - Fylo data storage component solution

This is a solution to the [Fylo data storage component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/fylo-data-storage-component-1dZPRbV5n). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

- Build out the project to the designs provided

### Links

- Solution URL: [Solution on Frontend Mentor]()
- Live Site URL: [Github Pages Link]()

## My process

### Built with

- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

In this project, I learned how to style a slider.

```html
<div class="slider-container">
        <p>
          You’ve used<strong> <span id="output-val"></span>GB </strong>of your
          storage
        </p>
        <input
          value="815"
          type="range"
          name="range"
          id="range"
          min="0"
          max="1000"
        />
        <div class="slider-labels">
          <p>0 GB</p>
          <p>1000 GB</p>
        </div>
        <div class="gb-left">
          <p><span class="gb-left-value" id="output"></span>GB LEFT</p>
        </div>
      </div>
    </div>
```

```css
input[type="range"] {
  -webkit-appearance: none;
}

input[type="range"]:focus {
  outline: none;
}
input[type="range"]::-webkit-slider-runnable-track {
  -webkit-appearance: none;
  border-radius: 40px;
  height: 15px;
  background: linear-gradient(to right, hsl(6, 100%, 80%), hsl(335, 100%, 65%));
}
input[type="range"]::-webkit-slider-thumb {
  -webkit-appearance: none;

  border: none;
  border-radius: 50%;
  height: 13px;
  width: 13px;
  max-width: 80px;
  position: relative;
  bottom: -1px;
  background-color: #fff;
  cursor: -webkit-grab;
}
```

## Author

- Website - [Landon Schlangen](https://www.landonschlangen.com)
- Frontend Mentor - [@Landon345](https://www.frontendmentor.io/profile/Landon345)
- LinkedIn - [Profile](https://www.linkedin.com/in/landon-schlangen-a3989a16b/)

## Acknowledgments

I completed this challenge in about 2.5 hours. I made the progress bar a slider for some reason. Oh well.

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
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![](screenshots/desktop-screenshot.jpg)
![](screenshots/mobile-screenshot.jpg)


### Links

- Solution URL: [Add solution URL here](https://github.com/mcdulingm/stats-preview-card)
- Live Site URL: [Add live site URL here](http://challenges.mroux.co.za/Challenges/Stats-Preview-Card-Component-Main/)

## My process

I probably should have started with a better process but sins it's my first challenge I just openend my Index file and worked my way outside in. I also focused on working from the mobile view to desktop

### Built with

- HTML
- CSS 
- Mobile-first workflow

### What I learned

I learned an alternative solution to switching images depending the screen size.

To see how you can add code snippets, see below:

```html
<picture>
	<source 
		media="(min-width: 650px)"
		srcset="images/image-header-desktop.jpg">
 	<source 
		media="(min-width: 480px)"
		srcset="images/image-header-mobile.jpg">
	<img 
		src="images/image-header-desktop.jpg" 
		alt="Statscard Information">
</picture>
```

### Continued development

There is so much I'm planning on learning. I want to focus more on my grid or flexbox solution for bigger projects. Also need to work on HTLM structure and naming conventions. Excited to get going.


## Author

- Frontend Mentor - [@mcdulingm](https://www.frontendmentor.io/profile/mcdulingm)

## Acknowledgments

Shout out to the future mentors in my life who will be helping me grow from this first upload.

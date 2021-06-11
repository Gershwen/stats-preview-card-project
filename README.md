# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

  - [The challenge](#the-challenge)
  - [Links](#links)
  - [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Author](#author)

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

## My process

I followed a mobile first approach. 
Applying HTML elements and css styling according to how the component will be viewed on mobile. Then I scaled it up using media querie to suite a desktop view.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

During this project I learned how to replace an image with another image using css. See below example: 

<!-- HTML -->
<img class="mobile-image" src="C:\Users\gersh\Desktop\stats-preview-card-component-main\images\image-header-mobile.jpg" alt="mobileimage">
    <img class="desktop-image" src="C:\Users\gersh\Desktop\stats-preview-card-component-main\images\image-header-desktop.jpg" alt="desktopimage">

    <!-- CSS -->
    <!-- mobile view -->
    .desktop-image{display: none;}

<!-- desktop view -->
.mobile-image{display: none;}

.desktop-image{display: block;}

## Author

- Frontend Mentor - [@Gershwen](https://www.frontendmentor.io/profile/Gershwen)


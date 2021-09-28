# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). 

## Table of contents

- [Overview](#overview)
- [The challenge](#the-challenge)
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


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://avedimusungu.github.io/stats-preview-card-component-main/)

## My process

### Built with

- Atom text editor
- Bootstrap 4.6 (for the grid layout)
- Scout App (for compiling my sass to css)

### What I learned

- I implemented Bootstrap into my HTML for the first time which gave me good practice on the grid layout.
- I learnt how to use media queries in building responsive sites
- I learnt how to use a compiler (Scout App) into my workflow. I wrote the majority of the code for styles in sass and Scout App converted it to css which was a big load off my back.

- Some code that i'm proud of:

```html
<div class="card container-fluid">
    <div class="sub-card row">

      <div class="sub-card-1 col-md-6">

        <h1 class="main-heading">Get <span class="accent">insights</span> that help your business grow.</h1>
        <div class="main-paragraph">
          Discover the benefits of data analytics and make better decisions regarding revenue, customer
          experience, and overall efficiency.
        </div>

        <div class="stats">
          <span class="stats-1">10k+</span> <br>
          <span class="stats-2">COMPANIES</span>
        </div>

        <div class="stats">
          <span class="stats-1">314</span> <br>
          <span class="stats-2">TEMPLATES</span>
        </div>

        <div class="stats">
          <span class="stats-1">12M+</span> <br>
          <span class="stats-2">QUERIES</span>
        </div>

      </div>

      <div class="sub-card-2 col-md-6">
        <img src="images\image-header-desktop.jpg" alt="">
      </div>

    </div>
```
```css
@media screen and (max-width: 768px) {

  body {
    font-size: 1rem;
  }

  .card {
    margin: 12rem;
    padding: 0;
    width: 50%;
  }

  .sub-card {
    display: flex;
    flex-flow: column-reverse;
  }

  .sub-card .sub-card-1 {
    text-align: center;
    padding: 10%;
  }
  
  .sub-card .sub-card-1 .main-heading {
    font-size: 2rem;
  }

  .sub-card .sub-card-1 .main-paragraph {
    margin: 2rem 0;
  }

  .sub-card .sub-card-1 .stats {
    display: block;
    padding: 1rem;
  }

  .sub-card .sub-card-2 {
    border-radius: 20px 20px 0 0;
  }

  .sub-card .sub-card-2 img {
    border-radius: 20px 20px 0 0;
  }

}
```

### Continued development

- Get better at implementing bootstrap in less time
- Understand implementing breakpoints using media queries in SASS/SCSS


### Useful resources

- [Making responsive sites](https://stackoverflow.com/questions/32829567/change-div-order-with-css-depending-on-device-width/32829829) - This helped me make my site mobile-friendly.
- [CSS Filter](https://www.w3schools.com/cssref/css3_pr_filter.asp) - This was a useful reference in formatting my image file.
- [How the bootstrap 4 grid works](https://uxplanet.org/how-the-bootstrap-4-grid-works-a1b04703a3b7) - This was a useful overview of the bootstrap grid layout.


## Author

- Frontend Mentor - [@AvediMusungu](https://www.frontendmentor.io/profile/AvediMusungu)



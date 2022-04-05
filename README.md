# Woodhouse Creative Website

## Table of contents

- [Overview](#overview)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Acknowledgments](#acknowledgments)


## Overview

I've been a professional photographer for two years under the name Photos by Sarah Wood. As I've picked up new skills in my graduate coursework, I felt inspired to rebrand my business and services to include other creative work. That's when Woodhouse Creative was born! 

Woodhouse Creative offers photography, brand design, and creative services to small business and individuals looking to make a splash in their industries. To successfully rebrand, I needed to create a new logo system and color palette, and restructure my business website.

This site is my first attempt at building a website using HTML and CSS. I'm excited to share my home page, about page, work page, and a sample project page.

## My process

### Built with

- Coolors (color palette inspiration)
- FontJoy (typography pairing inspiration)
- Adobe Illustrator (logo system and brand design)
- Adobe XD (site prototype)
- VS Code 

### What I learned

I learned so much through this project! The biggest thing was settling into a coding workflow that works well for me. I became really comfortable with
nesting in HTML, using classes and ID's to define consistent styles in CSS, and using CSS grid. I also became really comfortable with hover states. 
After I finished coding the homepage, the remaining pages went REALLY quickly and I was so happy with my progress.


Some code snippets I'm proud of, that challenged me at first:

```html
<body>
    <section class="work-recent-projects">
      <h4>Recent Projects</h4>
      <div class="category-menu">
        <a id="no-border" class="category-title" href="">recent</a>
        <a class="category-title" href="">brand design</a>
        <a class="category-title" href="">content creation</a>
        <a class="category-title" href="">graphic design</a>
        <a class="category-title" href="">photography</a>
        <a class="category-title" href="">videography</a>
        <a class="category-title" href="">web prototyping</a>
      </div>
    </section>
  
  <section class="about-colors">
      <div class="colors-from-home">
        <h4>Colors from Home</h4>
        <p>
          Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam
          nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat,
          sed diam voluptua. At vero eos et accusam et justo duo dolores et ea
          rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem
          ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur
          sadipscing elitr
        </p>
      </div>
      <div class="color-swatches">
        <div class="circle">
          <div id="tan"></div>
          <h6>Apron</h6>
        </div>
        <div class="circle">
          <div id="yellow"></div>
          <h6>Golden Hour</h6>
        </div>
        <div class="circle">
          <div id="blue"></div>
          <h6>Dutch Oven</h6>
        </div>
        <div class="circle">
          <div id="orange"></div>
          <h6>From Scratch</h6>
        </div>
        <div class="circle">
          <div id="green"></div>
          <h6>Gram's Garden</h6>
        </div>
        <div class="circle">
          <div id="black"></div>
          <h6>Cast Iron</h6>
        </div>
      </div>
    </section>
```
```css
.about-favorite-things {
  color: #534e2c;
  padding: 0rem 17rem 0rem 17rem;
  height: 60vh;
  background-image: url(../svg/Tree-Texture-Green.svg);
  background-repeat: no-repeat;
  background-size: 20%;
  background-position: left 100% top 100%;
}
```

### Continued development

My continued goals for this project include:
- Most importantly, attempting and then perfecting the responsive design. I should have incorporated this in my code from the start
- Incorporating a scrolling horizontal text animation - I tried many code snippets and none of them functioned like I envisioned
- Make the "reviews" carousel interactive with javascript
- Using javascript or another systme to filter "recent projects" by category
- Think about site content more strategically and add crucial sections to the "about" like FAQ's and preferred contact information
- Experiment with forms on the Inquire page


## Author

- Website - Sarah Wood (https://www.photosbysarahwood.com)
- Instagram [@photosbysarahwood](https://www.instagram.com/photosbysarahwood)


## Acknowledgments

- Don Wood, for encouragement and inspiration from the very, very beginning.
- Andrew Sipes, for his time, mentorship, and wizard abilities.
- Zack Turner, for his patience, hyperfocus, friendship, and eagerness to help.
- Atlantis Warren, for her collaboration, commiseration, and sense of humor.


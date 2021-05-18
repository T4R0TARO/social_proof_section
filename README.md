# Frontend Mentor - Social proof section solution

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

- View the optimal layout for the section depending on their device's screen size

### Screenshot
![image](https://user-images.githubusercontent.com/76195521/118722366-f1aaec00-b7e0-11eb-88ee-cb9b7dc22623.png)
![image](https://user-images.githubusercontent.com/76195521/118722285-d8a23b00-b7e0-11eb-8229-7fb155df8815.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [Styled Components](https://styled-components.com/) - For styles

### What I learned

```css
@media (min-width: 1080px)
{
    .main_grid 
    {
        display: grid;
        grid-gap: 100px;
        grid-template-columns: 1fr 1fr;
        grid-template-areas: 
        "toptxt rated"
        "social social"
        ;
    }

    .main_text_container 
    {
        grid-area: toptxt;
        display: flex;
        flex-direction: column;
        align-content: center;
        justify-content: center;
    }

```
Feeling more confident  with using gird and flex-box. I mainly apply grid to set the larger card containers to the general location of where I want them located and use flex-box to apply the finer details inside the card containers. 

### Continued development

````html
<div class="rated_container">
      <div class="reviews item">
      <div class="star_container">
        <img src="images/icon-star.svg" alt="golden star icon" class="star_icon">
        <img src="images/icon-star.svg" alt="golden star icon" class="star_icon">
        <img src="images/icon-star.svg" alt="golden star icon" class="star_icon">
        <img src="images/icon-star.svg" alt="golden star icon" class="star_icon">
        <img src="images/icon-star.svg" alt="golden star icon" class="star_icon">
    </div>
      <p class="rated_text">Rated 5 Stars in Reviews</p>
      </div>
      <div class="guru item">
      <div class="star_container">
        <img src="images/icon-star.svg" alt="golden star icon" class="star_icon">
        <img src="images/icon-star.svg" alt="golden star icon" class="star_icon">
        <img src="images/icon-star.svg" alt="golden star icon" class="star_icon">
        <img src="images/icon-star.svg" alt="golden star icon" class="star_icon">
        <img src="images/icon-star.svg" alt="golden star icon" class="star_icon">
      </div>
        <p class="rated_text">Rated 5 Stars in Report Guru</p>
      </div>
      <div class="besttech item">
      <div class="star_container">
        <img src="images/icon-star.svg" alt="golden star icon" class="star_icon">
        <img src="images/icon-star.svg" alt="golden star icon" class="star_icon">
        <img src="images/icon-star.svg" alt="golden star icon" class="star_icon">
        <img src="images/icon-star.svg" alt="golden star icon" class="star_icon">
        <img src="images/icon-star.svg" alt="golden star icon" class="star_icon">
    </div>
````

I manage to organize the star icons  within a card container but is very repetitive. I would like to find a way to re-create this with less lines of code. 

### Useful resources

- [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/CSS/grid-template-areas) - Where I go for reference when I need to review CSS Grid
- [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox) - Where I go for reference when I need to review CSS Flex-box

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@T4R0TARO](https://www.frontendmentor.io/profile/T4R0TARO)
- Twitter - [@taro_code](https://twitter.com/taro_code)

## Acknowledgments

After going through Wes Bos Course on Flex-box and CSS Grid it helped me better understand when and where to apply layout properties.


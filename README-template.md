# Frontend Mentor - Bento grid solution

This is a solution to the [Bento grid challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/bento-grid-RMydElrlOj). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

-   [Overview](#overview)
    -   [The challenge](#the-challenge)
    -   [Screenshot](#screenshot)
    -   [Links](#links)
-   [My process](#my-process)
    -   [Built with](#built-with)
    -   [What I learned](#what-i-learned)
    -   [Useful resources](#useful-resources)
-   [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

-   View the optimal layout for the interface depending on their device's screen size

### Screenshot

![![Screenshot desktop](desktop.png)](./images/desktop.png)
![![Screenshot table](table.png)](./images/table.png)
![![Screenshot mobile](mobile.png)](./images/mobile.png)

### Links

-   Solution URL: [Add solution URL here](https://your-solution-url.com)
-   Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

-   Semantic HTML5 markup
-   CSS custom properties
-   Flexbox
-   CSS Grid
-   Mobile-first workflow

### What I learned

As part of improving my CSS Grid skills, I completed a series of interactive exercises on [CSS Grid Garden](https://cssgridgarden.com/), which provided a hands-on approach to understanding grid properties. Additionally, a tutorial video by [ edsHTML ](https://www.youtube.com/watch?v=-muwduB2G1A&t=516s) was incredibly helpful for specific aspects like fitting images within the grid.

I also applied the BEM (Block Element Modifier) methodology in my code to ensure clean and maintainable naming conventions. Here’s a snippet of the project I worked on, showcasing a responsive design using CSS Grid:

```html
<main class="main-content">
    <section class="social-media">
        <h1 class="social-media__title">
            Social Media
            <span class="social-media__title-highlight"
                >10x Faster with AI</span
            >
        </h1>
        <img
            class="social-media__image"
            src="assets/images/illustration-five-stars.webp"
            alt="AI-enhanced image"
        />
        <p class="social-media__description">Over 4,000 Five-Star Reviews</p>
    </section>
    <!-- Additional sections omitted for brevity -->
</main>
```

CSS styles were applied using CSS Grid to create a layout that adjusts to different screen sizes:

```css
.main-content {
    display: grid;
    width: 100vw;
    gap: 1rem;
    max-width: 1400px;
    margin: auto;
    padding: 1rem;
    grid-template-columns: repeat(4, 1fr);
    grid-template-rows: repeat(10, 75px);
}

/* Example style for a grid item */
.social-media {
    grid-column: 2/4;
    grid-row: 1/5;
    background-color: var(--purple-500);
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
}
```

The combination of these resources and methodologies helped me consolidate my understanding of CSS Grid and how to efficiently integrate responsive, well-structured designs.

## Useful Resources

Throughout my learning process, I utilized a variety of resources that helped deepen my understanding of CSS Grid, BEM, and responsive design principles. Below is a list of the most useful ones:

-   **[CSS Grid Garden](https://cssgridgarden.com/):** An interactive game that helps users grasp the basics of CSS Grid through progressively challenging levels. It was essential for building my foundation.

-   **[YouTube Tutorial by edHTML on CSS Grid](https://www.youtube.com/watch?v=-muwduB2G1A&t=516s):** A comprehensive video tutorial that covers creating the same project but using a different strategy than the one I implemented. This resource served as a guide to solidify my understanding with practical examples.

These resources, combined, provided a solid foundation and best practices for working with CSS Grid and creating clean, maintainable code.

## Author

-   Frontend Mentor -
    [@CristinaOsorio](https://www.frontendmentor.io/profile/CristinaOsorio) - Linkedin -
    [Cristina Osorio](https://www.linkedin.com/in/maria-cristina-osorio-perez-b205a5187/) - [Web Site](https://makry-dev.vercel.app/)

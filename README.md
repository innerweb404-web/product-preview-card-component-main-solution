# Frontend Mentor - Product Preview Card Component Solution

This is my solution to the Product Preview Card Component challenge on Frontend Mentor
.
The challenge helps improve coding skills by building realistic frontend projects.

Table of Contents

- Overview

- The Challenge

- Screenshot

- Links

- My Process

- Built With

- What I Learned

- Continued Development

- Useful Resources

- Author

- Acknowledgments

## Overview
## The Challenge

Users should be able to:

View the optimal layout depending on their device's screen size (mobile, tablet, desktop).

See hover and focus states for interactive elements.

![](./Design/desktop.JPG.jpg)


Links

Solution URL:[ GitHub Repository](https://github.com/innerweb404-web/product-preview-card-component-main-solution.git)

Live Site URL: [View Live Site](https://innerweb404-web.github.io/product-preview-card-component-main-solution/)

## My Process
Built With

Semantic HTML5 markup

CSS custom properties

Flexbox

CSS Grid

Mobile-first workflow

Responsive design with media queries

## What I Learned

- During this project, I focused on creating a responsive layout that works for multiple devices.
Key highlights:

- Used media queries for mobile, tablet, and desktop breakpoints.

- Applied CSS Grid and Flexbox for layout flexibility.

- Optimized images for different screen sizes.

- Implemented hover/focus states for interactive elements like buttons.

- Learned how to dynamically style components with CSS properties.

Example snippet of responsive CSS for mobile devices:
```css


@media (min-width:1024px) {
    
    .container{
        display: grid;
        grid-template-columns: 500px 500px;
        column-gap: 0;
        height: 50vh;
        max-width: 1000px;
        justify-items: center;
        align-items: center;
    }
    .img-fig {
        background-image: url('image-product-desktop.jpg');
        background-position: center;
        background-repeat: no-repeat;
        background-size: cover;
        height: 100%;
        border-top-left-radius: 1rem;
        border-bottom-left-radius: 1rem;
        width: 100%;
    }

    .img-fig img {
        display: none;
    }

    .hero {
        height: 100%;
        width: 100%;
        justify-content: space-around;
        border-top-right-radius: 1rem;
        border-bottom-right-radius: 1rem;
    }
}
```

Full CSS includes breakpoints up to 1024px and styling adjustments for each device.

Continued Development

- Optimize CSS using clamp() for better responsive typography and button sizes.

- Implement dark/light mode toggle.

- Explore CSS animations for smoother hover effects.

Useful Resources

Frontend Mentor
 - Challenge inspiration and guidance.

MDN Web Docs
 - CSS Grid, Flexbox, and responsive design reference.

Author

Name: Bright AG

Frontend Mentor: @innerweb404-web

Twitter: @brigtWeb_3

Acknowledgments

Thanks to Frontend Mentor for providing realistic project challenges.

Inspired by community solutions and CSS best practices found on MDN.



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

Solution URL: GitHub Repository

Live Site URL: View Live Site

## My Process
Built With

Semantic HTML5 markup

CSS custom properties

Flexbox

CSS Grid

Desktop-first workflow

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

@media (max-width: 375px) {
  .container {
    display: flex;
    flex-direction: column;
    max-width: 90%;
  }
  .img-fig {
    height: 50rem;
    background-image: url("image-product-mobile.jpg");
    background-size: cover;
    background-position: center;
    border-radius: 0.8rem 0.8rem 0 0;
  }
  .hero .cart-btn {
    height: 3rem;
    border-radius: 10px;
    font-size: 0.7rem;
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

Frontend Mentor: @nnerweb404-web

Twitter: @brigtWeb_3

Acknowledgments

Thanks to Frontend Mentor for providing realistic project challenges.

Inspired by community solutions and CSS best practices found on MDN.



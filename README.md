# Frontend Mentor - Blogr landing page solution

This is my solution to the [Blogr landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blogr-landing-page-EX2RLAApP).

## The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

## Extra challenge

As an extra challenge I'll do the following things:

- Use fluid typography
- Improve keyboard accessibility for header & footer navigation so that users can use arrow keys and esc key
- Create custom focus state using sass mixin
- Make the website as accessible as I can

## Built with

- [Astro](https://astro.build/) - Static Site Generator
- Semantic HTML5 markup
- SCSS
- Vanilla CSS
- Vanilla JavaScript

## What I've learned

- I learned of the getBoundingClientRect() method and how it works. More specifically I used the width property of it to be able to make the main navigation responsive with JavaScript and not by using the css media query. Also, I used it to prevent dropdown menu to go outside the viewport. This method is used in Navigation.astro and ButtonDropdown.astro components.
- I learned about Location Interface and how by using window.location.pathname it's possible to make the link of a current page active. This method is used in Navigation.astro component.

## Useful resources

- [Fluid Typography - Smashing Magazine](https://www.smashingmagazine.com/2022/01/modern-fluid-typography-css-clamp/)
- [Accessible Astro Starter by Mark Teekman](https://github.com/markteekman/accessible-astro-starter) - This was my starting point for creating accessible navigation in Astro. I did the HTML structure a bit different, as I tried to make it more simple from mine point of view. The JavaScript code is mainly the same, but I did some minor changes.

# My Personal Website

## Overview

This is my personal website where I showcase my projects.
<a target="_blank" href="https://revou-fsse-jun25.github.io/milestone-1-regencode/">
    Website Link
<a>

### Styling
The style of the website is minimalist and simple, where the main colors are gray and black.
Additionally, the website utilizes parallax effect for a sense of 3d-ness by combining 
CSS's perspective attribute and translateZ to push the grid background into the z-plane,
Glassy-looking divs/sections are used which emphasizes this parallax effect even more.

### Font usage
This website uses two fonts, Gothic and Roboto. Gothic is used for emphasis
and heading, while Roboto is used for normal text.

### Flexbox usage
Flexbox is used responsively in "My Projects" section, where in mobile the
flex-direction is column, which places the image below the text. On larger screens
the flex-direction is row which places text and image side-by-side.
nth-of-child(even) pseudo element is used in order to reverse the flex-direction row
on even list indexes.

### Grid usage
Grid is used for the "Socials" sub-section in "Contact Me" section, where the grid
layout changes according to the device width:
- If device width<400px, grid is 6x1. (row x col)
- else if device width >= 400px but width < 600px, grid is 3x2.
- else if width >= 600px, grid is 2x3.

### Deployment
Currently deployed on GitHub Pages, but planning to deploy with custom domain after website is complete.


## Website sections

### About me
Provides a short description of myself, as well as external links to my GitHub and LinkedIn pages.

### Projects
Shows the projects I have developed and GitHub links to each project.

### Contact
Provides viewers a way to contact me through email by filling out the form and submitting.
I also provided my contacts for people to contact me through other methods.

## Features Implemented:

- [x] - Add info

- [ ] - Add pictures

- [x] - Styling 


## Tech Stack:
- HTML/CSS
- Vanilla JS

## AI Usage

AI helped in implementation of div panning design and parallax style,
however I still try to understand the implementation.
AI also helped in resolving various random issue such as "why does this section 
has left margin for no reason" 
Overall, I think AI is beneficial for the creation of this project, and also my own
learning.


## Deadline:

[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/akoVEwkh)

# Meet Paige Three – Fan Page

## Overview

**Meet Paige Three** is a responsive fan page dedicated to showcasing the runway looks, highlights, and memorable moments of **Paige Three**, a contestant from *RuPaul’s Drag Race UK Series 7*.

The website presents her looks throughout the competition, biographical information, video clips from the show, and curated references. The goal of this project was to practice **pure HTML, CSS, and Vanilla JavaScript** while implementing responsive design across multiple device orientations.

This project was built without frameworks or external libraries, focusing on **fundamental front-end development skills**.

---

# Features

## Runway Look Gallery

A chronological list of Paige Three’s competition looks.
Clicking on each look dynamically displays:

* A high-resolution image
* A detailed fashion description
* Smooth entry animations

All content updates dynamically using JavaScript.

---

## Biography Panel

A stylized bio card presenting:

* Drag name
* Pronouns
* Ethnicity
* Birthdate
* Age
* Location
* Series information
* Placement in the competition
* Win record

---

## Drag Race Clips

The page includes embedded videos from key episodes, including:

* Cast reveal
* Entrance moment
* Runways
* Critiques
* Talent show
* Rusical performance
* Elimination episode
* Finale performance

Navigation buttons allow users to move between episode groups.

---

## Quotes and Trivia

Additional sections provide:

* Paige Three’s entrance quote
* Lyrics from her performance
* Trivia about her drag family and background

---

# Responsive Design

The page was carefully optimized for multiple device types and orientations using **CSS media queries**.

Supported layouts include:

| Device  | Orientation    |
| ------- | -------------- |
| Phones  | Portrait       |
| Phones  | Landscape      |
| Tablets | Portrait       |
| Tablets | Landscape      |
| Desktop | Default layout |

Each layout adapts:

* image scaling
* content width
* typography
* video containers
* layout flow

The design avoids horizontal scrolling and maintains readability across devices.

---

# Technologies Used

## HTML5

Provides the structural layout of the page, including:

* semantic sections
* article elements
* figure and image elements
* ordered lists for runway looks
* embedded video frames

---

## CSS3

Custom styling includes:

* gradient backgrounds
* animated transitions
* hover interactions
* typography styling
* flexible layouts with Flexbox
* responsive media queries

Key design features include:

* drag-inspired color gradients
* animated media transitions
* adaptive typography
* flexible image containers

---

## Vanilla JavaScript

JavaScript powers all interactive elements of the site.

Main functionalities include:

### Dynamic Look Gallery

Selecting a runway look updates:

* the image
* the description text
* animation effects

The data for the looks is stored in a structured JavaScript array.

---

### Episode Navigation

Episode clips are grouped into sections that can be navigated using **Next Episode** and **Last Episode** buttons.

The script dynamically:

* shows the correct episode container
* hides others
* triggers video animations
* adjusts button visibility

---

### Animation Triggers

Animations are controlled by dynamically applying CSS classes when elements appear or update.

Examples include:

* image slide-in animations
* description text transitions
* video fade-ins

---

# Project Structure

```
project-folder
│
├── index.html
├── style.css
├── script.js
│
├── FotosCarmesí/
│   ├── runway images
│   ├── bio images
│   └── track record image
│
└── README.md
```

---

# Key JavaScript Concepts Used

* arrays of objects for structured content
* event listeners
* DOM manipulation
* dynamic image loading
* animation control with CSS classes
* responsive behavior detection

---

# Learning Objectives

This project focuses on mastering:

* responsive layout design
* clean HTML structure
* CSS Flexbox layout systems
* dynamic DOM updates
* animation timing
* responsive typography
* debugging layout issues across devices

The entire project was built **without frameworks**, emphasizing understanding of core web technologies.

---

# Credits and References

Information and media references used for the project include:

* RuPaul’s Drag Race Wiki
* Wikipedia entries related to the series
* Paige Three’s official Instagram
* WOW Presents Plus
* Official music videos referenced in the show

All images and videos belong to their respective owners and are used for **fan and educational purposes only**.

---

# Disclaimer

This fan page is a personal educational project created for entertainment and learning purposes.
No copyright infringement is intended.

All media rights belong to their original creators and distributors.

# AERO - CSS Animation Challenge

A landing page for a fictional electric mobility brand. This project was developed to explore how CSS transitions and hover states can create a more interactive, responsive, and premium user experience without relying on JavaScript.

## The Challenge

**Objective:** Implement CSS animations to enhance user interaction and interface responsiveness.

**Requirements:** Utilise hover effects, transitions, and transforms to bring static elements to life while maintaining a clean and professional layout.

## Implementation

This project deliberately avoids complex keyframe animations in favour of mastering the `transition` property combined with pseudo-classes (`:hover`). Key interactive elements include:

* **Interactive Navigation & Controls:** Buttons and links smoothly invert colours or shift states over a 0.3-second duration, providing immediate visual feedback to the user.
* **Image Scaling:** Using `transform: scale(1.1)` combined with `overflow: hidden`, the feature image  zooms in when hovered, drawing the user's attention to the product.
* **Spatial Elevation:** The sponsor cards utilise `transform: translateY(-5px)` on hover. This physically lifts the element upwards, creating a tactile, button-like feel.
* **Performance:** All animations target the `transform` and `opacity` properties (where possible) or rely on simple colour shifts, ensuring smooth rendering across standard web browsers.

## Getting Started

This is a static HTML and CSS project. No build tools or package managers are required.

1. Clone or download this repository.
2. Open the project directory.
3. Open `index.html` in a standard web browser.

## Built With

* HTML5
* CSS3
* Google Fonts

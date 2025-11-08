# Responsive Sticky Navigation Menu

This project is a complete, self-contained, responsive navigation bar for a modern single-page website. It features a "sticky" (fixed) position, a mobile-first hamburger menu, and all the necessary HTML, CSS, and JavaScript to be a drop-in component for any portfolio or landing page.

[Animation of the sticky navbar in action, showing both desktop and mobile (hamburger) versions]

## Key Features

  * **Responsive & Mobile-First:** The navbar automatically collapses into a full-screen hamburger menu on screens smaller than 800px.
  * **Sticky Position:** The navigation bar remains fixed to the top of the viewport (`position: fixed`) for easy access while scrolling.
  * **JavaScript-Powered:** Uses clean, vanilla JavaScript to toggle the mobile menu's open/closed state.
  * **Smart Mobile UX:** The mobile menu automatically closes when a navigation link is clicked, allowing the user to smoothly scroll to the new section without extra taps.
  * **Smooth Scrolling:** Implements the CSS `scroll-behavior: smooth;` property for clean, animated scrolling when section links are clicked.
  * **Pure CSS Animations:** Features a clean hamburger-to-"X" icon animation and link hover/focus effects using only CSS transitions and pseudo-elements.
  * **Scroll Effect:** A simple JavaScript listener changes the navbar's background on scroll, a common effect for sticky headers.

## Installation

This is a static web component. No complex installation or build steps are required.

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/dusfirefox/responsive-sticky-navbar.git
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd responsive-sticky-navbar
    ```
3.  **Open the file:**
    Simply open the `index.html` file in your favorite web browser.

## How to Use

To adapt this for your own project:

1.  **HTML:** Copy the `<header>...</header>` structure from `index.html` into your own page. Ensure your content sections have `id` attributes that match the `href` values in the navigation links (e.g., `<a href="#about-section">` links to `<section id="about-section">`).
2.  **CSS:** Link the `style.css` file in your HTML's `<head>`. You can customize the colors, fonts, and breakpoint (800px) by editing the CSS variables and media query.
3.  **JavaScript:** Link the `script.js` file at the bottom of your HTML `<body>`. It will work out of the box with the provided HTML structure.

## Technologies Used

  * **HTML5:** For the structure of the navigation and content sections.
  * **CSS3:** For all styling, layout, animations, and responsiveness.
      * Flexbox
      * Media Queries
      * CSS Transitions
      * Pseudo-elements
  * **Vanilla JavaScript (ES6+):** For DOM manipulation (`classList.toggle`) and event handling (`addEventListener`) to power the mobile menu.

## Author

  * **Name:** D Fire
  * **GitHub:** [dusfirefox](https://www.google.com/search?q=https://github.com/dusfirefox)

## License

This project is licensed under the MIT License.

# ui-assignment
This is a sample website for my ui-assignment

# UI Developer Assignment 

This project is a UI interface developed for a first-round interview assignment. It adheres to the following requirements:

-   **HTML5 & CSS3:** Utilizes modern HTML5 semantic tags and CSS3 properties.
-   **SCSS:** Styles are written using SCSS for better organization and maintainability.
-   **Responsive Design (No Framework):** The UI is fully responsive and adapts to different screen sizes without the use of frameworks like Bootstrap. Custom media queries and flexbox/grid are employed for responsiveness.
-   **Google Fonts:** Integrates the "Poppins" font from Google Fonts.
-   **jQuery:** Uses jQuery for minor DOM manipulation and interactivity (e.g., mobile navigation toggle).

## Project Structure


Based on the provided mock-ups and content, here's a plan to create the UI, adhering to all the specified requirements.

Project Structure:

ui-assignment/
├── css/
│   └── style.scss

├── images/
│   ├── color-icon.png
│   ├── color-icon2.png
│   ├── design.jpeg
│   ├── develop.jpeg
│   ├── home3_alt_half_media3.jpg
│   ├── logo.png
│   ├── nav.png
│   └── slider-1.png
│   ├── small_author.png
│   ├── strategy.png
│   ├── support.png
│   ├── texture.png
│   ├── white-icon.png
├── js/
│   └── script.js
├── index.html
└── README.md

HTML (index.html):

The HTML structure will be semantic, using HTML5 tags like <header>, <nav>, <main>, <section>, <footer>, <article>, etc.

SCSS (css/style.scss):

I'll use SCSS to structure the styles, leveraging features like variables, nesting, and mixins for responsiveness.



# UI Developer Assignment

This project is a UI interface developed for a first-round interview assignment. It adheres to the following requirements:

-   **HTML5 & CSS3:** Utilizes modern HTML5 semantic tags and CSS3 properties.
-   **SCSS:** Styles are written using SCSS for better organization and maintainability.
-   **Responsive Design (No Framework):** The UI is fully responsive and adapts to different screen sizes without the use of frameworks like Bootstrap. Custom media queries and flexbox/grid are employed for responsiveness.
-   **Google Fonts:** Integrates the "Poppins" font from Google Fonts.
-   **jQuery:** Uses jQuery for minor DOM manipulation and interactivity (e.g., mobile navigation toggle).

## Project Structure

ui-assignment/
├── css/
│   └── style.scss  // SCSS source file
├── images/         // All provided images
├── js/
│   └── script.js   // jQuery and custom JavaScript
└── index.html      // Main HTML file


## How to Run

1.  **Clone the repository (or download the files):**
    ```bash
    git clone <repository-url>
    cd ui-assignment
    ```
2.  **Compile SCSS to CSS:**
    You'll need a Sass compiler. If you have Node.js installed, you can use `node-sass`:
    ```bash
    npm install -g sass
    sass --watch css/style.scss:css/style.css
    ```
    (Keep this command running in your terminal while developing to automatically compile SCSS changes.)
    Alternatively, you can use a GUI compiler like Koala or configure your IDE (VS Code with Live Sass Compiler extension, etc.) to compile SCSS on save.
3.  **Open `index.html`:**
    Simply open the `index.html` file in your web browser.

## Features Implemented

* **Responsive Header:** Navigation adjusts for desktop and mobile (hamburger menu).
* **Hero Section:** Dynamic layout with content and image.
* **Feature Cards:** Displays key features in a clean, responsive grid.
* **Milestones Timeline:** A visual representation of milestones, adapting for smaller screens.
* **Contact Section:** A clear contact form with an accompanying image, responsive layout.
* **Footer:** Standard footer with navigation and contact information.

## Notes

-   **SCSS Variables:** Utilize variables for colors, fonts, and other design elements.
-   **Responsive Media Queries:** Employ custom media queries for different screen sizes.
-   **Flexbox/Grid:** Utilize flexbox and grid layouts

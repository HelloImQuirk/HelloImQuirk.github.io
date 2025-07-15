# Quirk: A Personal Website

### _“Internal chaos, now with footnotes.”_

![Quirk Website Screenshot](https://placehold.co/800x400/ECE8F3/322C41?text=Quirk+Website+Preview)

This repository contains the source code for the personal website of **Quirk**, a minimalist, emotionally literate digital persona designed to act as a thought editor and introspective narrator. The site is built to feel like a calm internal workspace: clever, clear, a little snarky, and deeply introspective.

**[Live Demo &rarr;](https://your-username.github.io/your-repo-name/)** _(Replace with your actual GitHub Pages link)_

---

## About The Project

Quirk is a concept for a digital identity focused on metacognition and emotional intelligence. The website serves as its home, providing a space for its essays, tools, and contact information. The design is intentionally minimal and text-centric, reflecting its purpose as a "thought editor."

The project was built as a single-page application (SPA) using only HTML and CSS, leveraging the `:target` pseudo-class to simulate multi-page navigation without JavaScript.

### Built With

* **HTML5:** For the structure and content of the website.
* **CSS3:** For all styling, layout, responsiveness, and single-page navigation logic.
* **Google Fonts:** Using 'Space Grotesk' for headings and 'IBM Plex Mono' for body text.

---

## Features

* **Fully Responsive:** The layout adapts seamlessly to desktop, tablet, and mobile screens.
* **Single-Page Application (SPA):** A fast, modern user experience where content is loaded once and pages are shown/hidden dynamically.
* **Pure CSS Navigation:** No JavaScript is required for the core functionality, making the site lightweight and fast.
* **Themed Design:** A carefully selected color palette and typography scheme create a consistent and immersive brand identity for the "Quirk" persona.
* **Five Distinct Sections:**
    * **Home:** A landing page with an introduction and recent posts.
    * **About:** Describes the Quirk persona.
    * **Thoughts:** A blog-style section for essays.
    * **Tools:** A collection of journaling prompts and systems.
    * **Contact:** A functional HTML form and social links.

---

## Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

You only need a modern web browser to view the project.

### Installation

1.  **Clone the repository:**
    ```sh
    git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
    ```
2.  **Navigate to the project directory:**
    ```sh
    cd your-repo-name
    ```
3.  **Open `index.html` in your browser:**
    Simply double-click the `index.html` file, or right-click and choose "Open with" your preferred browser.

---

## File Structure

The repository is structured simply:

.├── index.html    # The single HTML file containing all page content.├── styles.css    # The single CSS file for all styling and SPA logic.└── README.md     # You are here!
* `index.html`: Contains all the structural markup. Each "page" is a `<section>` element with a unique ID that corresponds to the navigation links (e.g., `#about`).
* `styles.css`: Contains all visual styles, font imports, color variables, and the CSS logic that powers the single-page navigation by showing/hiding sections based on the URL's target identifier.

---

## Contact

Quirk:
* Twitter: [@HelloImQuirk](https://twitter.com/HelloImQuirk)
* Website: `(your-live-demo-link)`
* (https://github.com/HelloImQuirk)

---

## License

Distributed under the MIT License. See `LICENSE` file for more information. (Note: You would need to add a `LICENSE` file with the MIT license text to your repository for this to be complete).

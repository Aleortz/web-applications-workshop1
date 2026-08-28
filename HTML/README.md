# Web Applications - Workshop 1: Website (only HTML)

**University:** Yachay Tech - School of Mathematical and Computational Sciences
**Course:** Web Applications (Semester II 2026)
**Instructor:** Prof. Francisco Hidrobo
**Authors:** [Tu Nombre] & Demian Viteri
**Program:** Computer Science, 7th Semester

## Objective
Create a website consisting of at least four interconnected pages, using only HTML5.

## Prerequisites
To run this project locally with the custom domain, you need to edit your `hosts` file:
1. Add the following line to your OS `hosts` file:
   `127.0.0.1 workshop1.webapp`
2. Install a web server (e.g., Apache, Nginx) on your machine.
3. Create a virtual host mapping `workshop1.webapp` to the `my-site` directory.

## Project Structure
```text
my-site/
├── index.html
├── pages/
│   ├── courses.html
│   ├── schedule.html
│   ├── hobbies.html
│   └── contact.html
└── images/
    ├── Logo-YT-Azul-Transparencia.png
    └── profile.jpg
```

## Features
* **Semantic HTML:** Use of `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, and `<footer>`.
* **Navigation:** Fully interconnected pages using a central `<nav>` menu.
* **Tables:** A class schedule utilizing `rowspan` and `colspan`.
* **Forms:** A contact form utilizing various input types (text, email, date, number, select).

## Results Achieved
* **Structure:** Successfully built a fully functional HTML5 website with a solid semantic foundation.
* **Navigation:** Implemented seamless navigation across all 5 pages.
* **Data Presentation:** Created a detailed 7th-semester weekly class schedule using HTML tables, successfully managing complex cell spanning (`rowspan`, `colspan`) for overlapping hours.
* **User Input:** Designed a comprehensive contact form to capture user data using native HTML5 input validations.
* **Deployment:** Successfully configured the local web server and virtual host to serve the site under the custom `workshop1.webapp` domain.

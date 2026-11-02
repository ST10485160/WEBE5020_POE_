# Marconi Beam Secondary School Website

**Module:** WEBE5020 Website Development, Portfolio of Evidence
**Student:** Luvuyo | **Student number:** ST10485160
**Lecturer:** Mr Sibene | **Institution:** Rosebank International

## Project overview

A responsive website for Marconi Beam Secondary School. It gives parents, learners and prospective students information about the school and a way to ask questions. This repository contains the school website only. The gym website from the Part 1 proposal is not part of this repository.

## Pages

| Page | File |
|---|---|
| Home | `index.html` |
| About Us | `about.html` |
| Academics | `academics.html` |
| Admissions | `admissions.html` |
| Enquiry | `enquiry.html` |
| Contact Us | `contact.html` |

## Design

- Colours: maroon, white and gold (from the Part 1 proposal)
- Fonts: Times New Roman for headings, Arial for body text
- Responsive layout with media queries for desktop, tablet and mobile

## Folder structure

```
index.html, about.html, academics.html, admissions.html, enquiry.html, contact.html
css/style.css
js/
images/
```

## Technologies

HTML5, CSS3, JavaScript

## Changelog

### Part 2 feedback corrections

- **Added `css/style.css` to the repository.** The Part 2 submission did not include the stylesheet, so the pages loaded without any styling. The stylesheet now sits in the `css/` folder and every page links to it with `<link rel="stylesheet" href="css/style.css">`.
- **Rewrote the README.** The old README mixed the FitLife Gym proposal with the Marconi Beam School project. It now describes the school website only.
- **Filled in `enquiry.html`.** The file was empty (0 KB). It now has the full page layout, with the form to follow in Part 3.

### Part 3 changes

- **Shared layout on every page.** Each page now uses the same header, navigation bar and footer. The navigation marks the current page with `aria-current="page"`.
- **One `<h1>` per page.** The main heading of each page was changed from `<h2>` to `<h1>`, with `<h2>` used for sub-sections.
- **Unique titles and meta descriptions.** Every page has its own `<title>` and `<meta name="description">`.
- **Descriptive alt text.** Image alt text was changed from one-word labels (for example "Students") to descriptions of what the image shows.
- **Accessibility.** Added a "Skip to main content" link, visible keyboard focus outlines and reduced-motion support.

## References

- W3Schools. HTML and CSS tutorials. https://www.w3schools.com
- MDN Web Docs. https://developer.mozilla.org
- GitHub Docs. https://docs.github.com

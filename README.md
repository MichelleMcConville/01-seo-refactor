# Horiseon Website Refactoring

## Customer Request
For this project the customer request that we 

1. The site meets accessibility standards
2. Verify & fix the following source code if needed
    - Elements, Elements & Title
    - Alt & Heading attributes
    - HTML & CSS fall in sequential order
    - Styling & Structure
---

## Changes

### index.html
- Added the viewport meta tag below the `<html>` at top
- `Head `Updated the title to be more specific
- `Main `Changed the tag: `<body>` to `<main>`
- `Main:Header `Changed the tag: `<div>` to `<header>` & took out class attribute
- `Main:Header `Changed the tag: `<div>` to `<nav>`
- `Main:Header `Reformated the list items to be on one line per item
- `Main:Figure `Changed the tag for Hero attribute: `<div>` to `<figure>`
- `Main:Section `Changed the tag: `<div>` to `<section>`
- `Main:Section/Article `Changed the tags in the `<section>` (3x): `<div> ` to `<article>`
- `Main:Section/Article `Added missing `id=` attribute to the 1st image element
- `Main:Section/Article `Added the missing `alt=` attributes to all (3x) image elements
- `Main:Section/Article `Deleted the ` / ` at the end of all (3x) image elements
- `Main:Section/Article `Reformated the (3x) paragraph elements
- `Main:Aside `Changed the tag: `<div>` to `<aside>`
- `Main:Aside/Figure `Changed the tags in the `<aside>` (3x): `<div>` to `<Figure>`
- `Main:Aside/Figure `Added the missing `alt=` attributes to all (3x) image elements
- `Main:Aside/Figure `Deleted the ` / ` at the end of the first Two image elements
- `Main:Aside/Figure `Deleted the `></img` at the end of the 3rd element
- `Main:Aside/Figure `Reformated the (3)x paragraph elements
- `Main:Footer `Changed the tag: `<div>` to `<footer>` & took out class attribute
- Added inline comments throughout the code

### style.css
- Added inline comments throughout the code
- Deleted the `"."` in all the `header` selectors (6x)
- Changed `div` to `nav` in (3x) `Header` selectors
- Moved the `p` selector down to the `Main` area & below the `.content ` selector
- Combined all common selectors into one; in both the `Section w/ Articles ` & `Aside w/ Figures` areas
- Deleted the selectors left over from note above
- Reorganized areas in the CSS to match the same flow of the HTML
- Created the following areas:
    - `Main, Header, Figure, Section w/ Articles, Aside w/ Figures & Footer`
---

## Sources Referenced 

[w3schools](https://www.w3schools.com/html/html5_semantic_elements.asp) `   &   ` 
[Mastering Markdown](https://guides.github.com/features/mastering-markdown/) `   &   ` 
[google](https://www.google.com/)

---

## Output for Review

Submitted the following for review:

- The URL of the deployed application.
- The URL of the GitHub repository. (README.md included)
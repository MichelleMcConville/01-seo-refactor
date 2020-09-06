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
- `Head `Added the viewport meta tag
- `Head `Updated the title to be more specific
- `Body:Header `Changed the class header element: `<div>` to `<header>`
- `Body:Header `Changed the div element for the ul: `<div>` to `<nav>`
- `Body:Header `Reformated the list items to be on one line per item
- `Body:Figure `Changed the hero class element: `<div>` to `<figure>`
- `Body:Main `Changed the content class element: `<div>` to `<main>`
- `Body:Main/Article `Changed the contact class sub elements (3): `<div>` to `<article>`
- `Body:Main/Article `Added missing `id=` tag to the 1st article element
- `Body:Main/Article `Added the missing alt attributes to the (3) images
- `Body:Main/Article `Deleted the `/` at the end of the (3) elements
- `Body:Main/Article `Reformated the (3) paragraph elements
- `Body:Aside `Changed the benefits class element: `<div>` to `<aside>`
- `Body:Aside/Section `Changed the benefits class sub elements: `<div>` to `<section>`
- `Body:Aside/Section `Added the missing alt attributes to the (3) images
- `Body:Aside/Section `Deleted the `/` at the end of the first (2) elements
- `Body:Aside/Section `Deleted the `></img` at the end of the third element
- `Body:Aside/Section `Reformated the (3) paragraph elements
- `Body:Footer `Changed the class footer element: `<div>` to `<footer>`
- Added inline comments throughout the code

### style.css
- Added inline comments throughout the code
- Changed `<div>` to `<nav>` in (3) `Header` selectors
- Moved the `p` selector down to the `Main` section below the `content `selector
- Moved the `.benefit` selectors into `Aside..` section below `Articles`
- Reorganized the `Articles` section
- Reorganized the `.benefit` selectors
- Created the following sections:
    - `Header, Figure, Main, Articles, Aside w/ Sections & Footer`
---

## Sources Referenced 

[w3schools](https://www.w3schools.com/html/html5_semantic_elements.asp) `   &   ` 
[Mastering Markdown](https://guides.github.com/features/mastering-markdown/) `   &   ` 
[google](https://www.google.com/)

---

## Output for Review

You are required to submit the following for review:

- The URL of the deployed application.
- The URL of the GitHub repository. (Include a README)
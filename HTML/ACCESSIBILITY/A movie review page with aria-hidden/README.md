# Accessible Movie Review Project – *RISE BEYOND*

This project is part of a FreeCodeCamp HTML lab and is focused on building a **semantically correct** and **accessible** movie review page using HTML5 and ARIA attributes.

## Objective
Create a simple webpage that uses semantic HTML and basic ARIA attributes to ensure better accessibility, particularly for screen readers.

## Accessibility Features
- Semantic structure using `<main>`, `<h1>`, `<h2>`, `<ul>`, and `<strong>` elements
- Descriptive `alt` text for the movie image
- `aria-hidden="true"` used on the visual star rating to hide it from screen readers
- Clear textual numeric rating included after the stars for accessibility

## Features Implemented
- Movie title with a semantic heading (`<h1>`)
- Cover image with `alt` text
- Description in a `<p>` tag
- Movie rating in a `<p>`:
  - `<strong>` for "Movie Rating:"
  - `<span aria-hidden="true">` for visual star rating
  - Numeric rating included for screen readers
- Cast list using `<ul>` and `<li>`, with actor names in `<strong>`

## Tools Used
- HTML5  
- ARIA attributes for accessibility  
- FreeCodeCamp-provided assets

## Image Source
- Movie cover from FreeCodeCamp:  
  `https://cdn.freecodecamp.org/curriculum/labs/rise-beyond-2.png`

## Author
Created by a FreeCodeCamp student with a focus on web accessibility and semantic HTML.

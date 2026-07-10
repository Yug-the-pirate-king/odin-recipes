# Odin Recipes

## Table of Contents
- [Description](#description)
- [Skills Demonstrated](#skills-demonstrated)
- [Project Structure](#project-structure)
- [Prerequisites](#prerequisites)
- [How to View](#how-to-view)
- [Error Handling & Validation](#error-handling--validation)
- [Contributing](#contributing)
- [Future Improvements](#future-improvements)
- [License](#license)

## Description

A basic recipe website built as part of The Odin Project's Foundation course. The project intentionally focuses on HTML structure before adding CSS styling, so the pages will not look visually polished yet.

The site includes:
- A main index page with links to multiple recipes.
- Individual recipe pages featuring images, descriptions, ingredients, and numbered preparation steps.

## Skills Demonstrated

- Structuring documents with **HTML5**.
- Writing standard HTML **boilerplate** (`<!DOCTYPE html>`, `<html>`, `<head>`, `<body>`, etc.).
- Creating internal links with **anchor tags** (`<a>`).
- Displaying images with **image tags** (`<img>`) and descriptive `alt` text.
- Organizing content with **unordered** (`<ul>`) and **ordered** (`<ol>`) lists.
- Managing project files and folders in a **Git** repository.

## Project Structure

- `index.html` — landing page with recipe links.
- `recipes/` — directory containing individual recipe pages.
- `images/` — directory for recipe images (add as the project grows).

## Prerequisites

- A modern web browser.
- Git, if cloning the repository locally.

## How to View

1. Clone the repository: `git clone https://github.com/Yug-the-pirate-king/odin-recipes.git`
2. Navigate into the project folder: `cd odin-recipes`
3. Open `index.html` in your browser. For example:
   - macOS: `open index.html`
   - Windows PowerShell: `start index.html`
   - Or double-click the file in your file manager.

## Error Handling & Validation

To keep the project robust and easy to maintain:
- Validate all HTML files with the [W3C Markup Validation Service](https://validator.w3.org/) before committing.
- Confirm that every `<img>` tag has a valid `src` path and a meaningful `alt` attribute.
- Check that all internal links use relative paths and point to existing files.
- When adding a new recipe, ensure it contains:
  - A title
  - A description
  - An ingredients list
  - Numbered preparation steps
  - An image reference

## Contributing

When contributing a new recipe:
1. Add a new HTML page inside the `recipes/` directory.
2. Follow the existing HTML boilerplate and semantic structure.
3. Validate the page and verify all links and image paths.
4. Add a corresponding link in `index.html`.

## Future Improvements

- Apply CSS styling and responsive layout.
- Add project screenshots to this README.
- Improve accessibility with semantic tags, ARIA labels, and color-contrast considerations.

## License

This project is for educational purposes as part of [The Odin Project](https://www.theodinproject.com/) curriculum.
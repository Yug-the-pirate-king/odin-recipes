<!-- README.md - Odin Recipes -->
<!-- Documentation for a basic recipe website built with The Odin Project. -->

# Odin Recipes

## Table of Contents
<!-- Navigation map linking to each documented section. -->
- [Description](#description)
- [Skills Demonstrated](#skills-demonstrated)
- [Project Structure](#project-structure)
- [Prerequisites](#prerequisites)
- [How to View](#how-to-view)
- [Error Handling & Validation](#error-handling--validation)
- [Recipe Requirements](#recipe-requirements)
- [Contributing](#contributing)
- [Future Improvements](#future-improvements)
- [License](#license)

## Description

<!-- Overview of the project's purpose and current scope. -->
A basic recipe website built as part of The Odin Project's Foundation course. The project intentionally focuses on HTML structure before adding CSS styling, so the pages will not look visually polished yet.

The site includes:
- A main index page with links to multiple recipes.
- Individual recipe pages featuring images, descriptions, ingredients, and numbered preparation steps.

## Skills Demonstrated

<!-- List of technical skills practiced while building this project. -->
- Structuring documents with **HTML5**.
- Writing standard HTML **boilerplate** (`<!DOCTYPE html>`, `<html>`, `<head>`, `<body>`, etc.).
- Creating internal links with **anchor tags** (`<a>`).
- Displaying images with **image tags** (`<img>`) and descriptive `alt` text.
- Organizing content with **unordered** (`<ul>`) and **ordered** (`<ol>`) lists.
- Managing project files and folders in a **Git** repository.

## Project Structure

<!-- Breakdown of the repository layout and the purpose of each directory. -->
- `index.html` — landing page with recipe links.
- `recipes/` — directory containing individual recipe pages.
- `images/` — directory for recipe images (add as the project grows).

## Prerequisites

<!-- Environment requirements for viewing or contributing to the project. -->
- A modern web browser.
- Git, if cloning the repository locally.

## How to View

<!-- Step-by-step instructions for running the project locally. -->
1. Clone the repository:
   ```bash
   git clone https://github.com/Yug-the-pirate-king/odin-recipes.git
   ```
2. Navigate into the project folder:
   ```bash
   cd odin-recipes
   ```
3. Open `index.html` in your browser. For example:
   - macOS: `open index.html`
   - Windows PowerShell: `start index.html`
   - Or double-click the file in your file manager.

## Error Handling & Validation

<!-- Quality assurance rules to keep the project robust and easy to maintain. -->
To keep the project robust and easy to maintain:
- Validate all HTML files with the [W3C Markup Validation Service](https://validator.w3.org/) before committing.
- Confirm that every `<img>` tag has a valid `src` path and a meaningful `alt` attribute.
- Check that all internal links use relative paths and point to existing files.
- Ensure every new recipe satisfies the [recipe requirements](#recipe-requirements).

## Recipe Requirements

<!-- Centralized checklist reused by the validation and contributing sections. -->
Every recipe page must contain the following:

- A title.
- A description.
- An ingredients list.
- Numbered preparation steps.
- A valid image reference.

## Contributing

<!-- Process for adding new recipes while maintaining project consistency. -->
When contributing a new recipe:

1. Add a new HTML page inside the `recipes/` directory.
2. Follow the existing HTML boilerplate and semantic structure.
3. Ensure the page meets the [recipe requirements](#recipe-requirements).
4. Validate the page and verify all links and image paths.
5. Add a corresponding link in `index.html`.

## Future Improvements

<!-- Planned enhancements for subsequent iterations of the project. -->
- Apply CSS styling and responsive layout.
- Add project screenshots to this README.
- Improve accessibility with semantic tags, ARIA labels, and color-contrast considerations.

## License

<!-- Legal and attribution information. -->
This project is for educational purposes as part of [The Odin Project](https://www.theodinproject.com/) curriculum.
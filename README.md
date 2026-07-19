# Odin Recipes

> A simple, static recipe website built as part of [The Odin Project](https://www.theodinproject.com/) Foundation course.

## Table of Contents

- [Description](#description)
- [Features](#features)
- [Skills Demonstrated](#skills-demonstrated)
- [Project Structure](#project-structure)
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
- [Error Handling & Validation](#error-handling--validation)
- [Contributing](#contributing)
- [Roadmap](#roadmap)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Description

Odin Recipes is a beginner-friendly recipe website created to practice core HTML concepts. The project intentionally focuses on semantic HTML structure before introducing CSS, so the visual presentation remains minimal at this stage.

The website currently includes:

- A main index page that links to multiple recipes.
- Individual recipe pages containing:
  - A descriptive title.
  - A brief description.
  - An ingredients list.
  - Numbered preparation steps.
  - An illustrative image.

## Features

- Static, multi-page recipe site.
- Semantic HTML5 markup.
- Internal navigation via relative links.
- Accessible image tags with descriptive `alt` text.
- Organized content using unordered and ordered lists.

## Skills Demonstrated

- Structuring documents with **HTML5**.
- Writing standard HTML boilerplate (`<!DOCTYPE html>`, `<html>`, `<head>`, `<body>`).
- Creating internal links with **anchor tags** (`<a>`).
- Displaying images with **image tags** (`<img>`) and descriptive `alt` text.
- Organizing content with **unordered** (`<ul>`) and **ordered** (`<ol>`) lists.
- Managing project files and folders in a **Git** repository.

## Project Structure

```text
odin-recipes/
├── index.html        # Landing page with recipe links
├── recipes/          # Individual recipe pages
└── images/           # Recipe images (added as project grows)
```

## Prerequisites

- A modern web browser.
- Git (optional, only if cloning the repository locally).

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/Yug-the-pirate-king/odin-recipes.git
   ```

2. Navigate into the project directory:

   ```bash
   cd odin-recipes
   ```

3. Open `index.html` in your browser:

   ```bash
   # macOS
   open index.html

   # Windows PowerShell
   start index.html

   # Linux
   xdg-open index.html
   ```

   Alternatively, double-click `index.html` in your file manager.

## Error Handling & Validation

To keep the project robust and maintainable:

- Validate all HTML files with the [W3C Markup Validation Service](https://validator.w3.org/) before committing.
- Confirm every `<img>` tag has a valid `src` path and a meaningful `alt` attribute.
- Verify all internal links use relative paths and point to existing files.
- When adding a new recipe, ensure it contains:
  1. A title
  2. A description
  3. An ingredients list
  4. Numbered preparation steps
  5. An image reference

## Contributing

Contributions are welcome. To add a new recipe:

1. Create a new HTML page inside the `recipes/` directory.
2. Follow the existing HTML boilerplate and semantic structure.
3. Validate the page and verify all links and image paths.
4. Add a corresponding link in `index.html`.

## Roadmap

- [ ] Apply CSS styling and responsive layout.
- [ ] Add project screenshots to this README.
- [ ] Improve accessibility with semantic tags, ARIA labels, and color-contrast considerations.

## License

This project is for educational purposes as part of [The Odin Project](https://www.theodinproject.com/) curriculum.

## Acknowledgments

- Built as part of [The Odin Project](https://www.theodinproject.com/) curriculum.
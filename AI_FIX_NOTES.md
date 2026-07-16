# AI Fix — Issue #5: Maintenance: Add comprehensive docstrings

**Issue body:**

This is an automated issue created by the AI agent to track planned code quality improvements. The AI will fix this in a subsequent run.

---

**AI-proposed fix:**

### Root cause

The repository currently lacks inline documentation. HTML pages have no file-level or section comments, CSS has no header documentation, and any JavaScript functions lack JSDoc-style docstrings. This makes the codebase harder to maintain, review, and onboard new contributors to.

### Exact code changes needed

Apply the following documentation blocks to **every** relevant file in the repo. Paths below match the typical Odin Recipes structure; replace filenames with the actual files in your tree.

#### 1. `index.html`
Add a file-level comment right after `<!DOCTYPE html>`:

```html
<!DOCTYPE html>
<!--
  Odin Recipes — Homepage
  Lists all available recipes and links to each recipe page.
  Project: The Odin Project — Foundations Course
-->
<html lang="en">
<head>
  ...
```

#### 2. `recipes/<recipe-name>.html` (e.g., `recipes/lasagna.html`)
Add a file-level comment describing that specific recipe page:

```html
<!DOCTYPE html>
<!--
  Odin Recipes — Lasagna Recipe Page
  Displays the ingredients, steps, and image for lasagna.
-->
<html lang="en">
<head>
  ...
```

Add section comments inside the body where it helps readability:

```html
<!-- Recipe header: title + image -->
<section class="recipe-header">...</section>

<!-- Ingredients list -->
<section class="ingredients">...</section>

<!-- Cooking instructions -->
<section class="steps">...</section>
```

#### 3. `styles.css`
Add a CSS file-level docstring at the top:

```css
/**
 * styles.css
 * Global stylesheet for the Odin Recipes project.
 * Contains base typography, layout, recipe cards, and responsive rules.
 */
```

Then add section banners:

```css
/* ================= Base / Reset ================= */

/* ================= Layout ================= */

/* ================= Recipe components ================= */
```

#### 4. `scripts.js` (if any JavaScript exists)
Add a module-level JSDoc and document every function:

```js
/**
 * script.js
 * Shared client-side utilities for the Odin Recipes project.
 */

/**
 * Renders a recipe card in the DOM.
 *
 * @param {Object} recipe - The recipe data.
 * @param {string} recipe.title - The recipe title.
 * @param {string} recipe.imageUrl - URL of the recipe image.
 * @param {string} recipe.link - URL to the full recipe page.
 * @returns {HTMLElement} The constructed recipe card element.
 */
function createRecipeCard(recipe) {
  // implementation
}
```

### Follow-up actions

1. Audit every `.html`, `.css`, and `.js` file and apply the patterns above.
2. Open a single PR titled something like `docs: add comprehensive file-level and function docstrings`.
3. Add a short “Documentation” note to `CONTRIBUTING.md` (or the README) requiring:
   - HTML file-level comments,
   - CSS section comments,
   - JSDoc for all JavaScript functions.
4. Consider enabling a linter rule for missing JSDoc (e.g., ESLint `require-jsdoc` or `eslint-plugin-jsdoc`) if the project grows beyond static HTML.
5. Close Issue #5 once the PR is merged.

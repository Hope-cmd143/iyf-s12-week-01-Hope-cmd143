# Accessibility (a11y) Report

## Overview
This report evaluates the accessibility practices implemented across the portfolio website to ensure it is usable by individuals with diverse abilities and assistive technologies.

## Key Accessibility Features Implemented
1. **Semantic HTML Elements:** Used tags like `<header>`, `<nav>`, `<main>`, `<article>`, and `<footer>` so screen readers can easily interpret the page structure.
2. **Accessible Form Controls:** Linked all form `<label>` elements explicitly to their respective inputs using `for` and `id` attributes, alongside a `<fieldset>` and `<legend>` for grouped elements and required fields.
3. **Alt Text for Images:** Added descriptive `alt` attributes to all images to ensure screen reader users understand visual content.
4. **Keyboard Navigation:** Ensured interactive elements like links and form fields are fully reachable and navigable using the `Tab` key.

## Areas for Improvement & Future Testing
- Run automated accessibility audits using tools like **Lighthouse** or **WAVE** to catch any missing contrast ratios orARIA attributes.
- Perform a manual keyboard-only test across all pages to verify focus states are clearly visible.
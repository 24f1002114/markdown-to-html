## Overview

This web application takes a Markdown input and renders it as HTML within a designated div element (`#markdown-output`). It utilizes the `marked` library for Markdown parsing and `highlight.js` for syntax highlighting of code blocks. It provides a tabbed interface to switch between the rendered HTML and the original Markdown source. Additionally, it displays a live word count badge that updates after every render and formats numbers with Intl.NumberFormat.

## Setup

1.  Ensure you have the `index.html` file.
2.  No specific setup is required as it uses CDN links for external libraries.

## Usage

1.  Open `index.html` in a web browser.
2.  The default Markdown content will be rendered as HTML inside the `#markdown-output` div.
3.  Code blocks will be syntax highlighted.
4.  Use the tabs to switch between the rendered HTML view and the raw Markdown source view.
5.  The word count is displayed and automatically updates when the content changes.

## Improvements from Previous Version

The primary enhancements include:

1.  **Live Word Count:** A word count badge (`#markdown-word-count`) has been added.  It updates dynamically after each render, providing immediate feedback on the length of the Markdown content.
2.  **Number Formatting:** The word count is formatted using `Intl.NumberFormat` for improved readability, especially for large documents.
3.  **Code Clarity:** The JavaScript code has been refactored for better readability and maintainability.
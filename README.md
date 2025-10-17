## Overview

This web application takes a Markdown file (input.md) and renders it as HTML within a designated div element (`#markdown-output`). It utilizes the `marked` library for Markdown parsing and `highlight.js` for syntax highlighting of code blocks.  It also provides a tabbed interface to switch between the rendered HTML and the original Markdown source.

## Setup

1.  Ensure you have the `index.html` and `input.md` files in the same directory.
2.  No specific setup is required as it uses CDN links for external libraries.

## Usage

1.  Open `index.html` in a web browser.
2.  The content of `input.md` will be rendered as HTML inside the `#markdown-output` div.
3.  Code blocks in `input.md` will be syntax highlighted.
4.  Use the tabs to switch between the rendered HTML view and the raw Markdown source view.

## Improvements from Previous Version

The primary enhancement is the addition of a tabbed interface.  Users can now easily switch between viewing the rendered HTML output and the original Markdown source code. This provides a convenient way to compare the original Markdown with its rendered output and inspect the underlying code. The content between tabs stays in sync.
# CLAUDE.md

This file provides guidance to Claude when working with code in this repository.

## Stack & Conventions

**Hard constraints — do not violate these:**

1. **Single-file project.** The entire project must live in one `index.html` file, with all CSS and JavaScript inlined directly in that file using `<style>` and `<script>` tags — never in separate `.css` or `.js` files, and never split across multiple HTML pages. Linking external images, CSS libraries, and JavaScript libraries (e.g. via `<link>`/`<script src>` to a CDN) is allowed. No additional pages of any kind. This constraint exists so the finished project can be copy-pasted as a single file for sharing in class and on single-file code platforms (e.g. CodePen, JSFiddle).
2. **Vanilla only.** Use plain HTML, CSS, and JavaScript only. No frameworks or libraries that require a build step (no React, Vue, TypeScript, Sass, JSX, bundlers, etc.), and no build/compile step of any kind. The file must run as-is when opened directly in a browser.

## Tech stack (hard constraints — do not deviate)
- Vanilla HTML, CSS, and JavaScript only. No React, Vue, or any JS framework.
- Tailwind CSS for all styling (via CDN only).
- No backend, no database. Fully static site.
- A toggle for light and dark theme, with the choice remembered
  across visits.

# Series Reference

## Purpose

This document is the curated source-reference overview for the Simple Website Examples series.

It consolidates the useful high-level material from earlier source-reference documents while preserving the original inputs under `docs/source-reference/archive/`.

Use this file when you want a single reference for:

- What the series is
- Who it is for
- How the repositories fit together
- What each example demonstrates
- How the file structures progress across the series

The active hub documentation remains the primary current documentation. This file is a curated reference that supports the active docs.

---

## Series Overview

Simple Website Examples is a progressive series of small, plain HTML, CSS, and JavaScript website examples.

The series is intentionally minimal:

- No frameworks
- No package managers
- No build tools
- No backend
- No database
- No unnecessary abstraction

Each example introduces one or a small number of new concepts while keeping the code easy to read and compare.

The goal is not to build production-ready applications. The goal is to provide clear reference examples for how static websites are structured and how common website concepts build on one another.

---

## Repository Model

The final repository model uses one hub repo plus 18 standalone website example repos.

```text
simple-website-examples
simple-website-01-first-web-page
simple-website-02-basic-site-files
simple-website-03-html-css-js-assets
simple-website-04-multi-page-site
simple-website-05-maintainable-file-structure
simple-website-06-basic-forms
simple-website-07-form-validation
simple-website-08-images-and-gallery
simple-website-09-responsive-layout-basics
simple-website-10-head-metadata-and-favicon
simple-website-11-accessibility-basics
simple-website-12-navigation-and-usability
simple-website-13-open-graph-and-metadata
simple-website-14-javascript-organization
simple-website-15-expanded-form-controls
simple-website-16-accessibility-refinements
simple-website-17-responsive-layout-refinements
simple-website-18-media-and-embeds
```

The former documentation-only Project 19 content is incorporated into the hub repo:

```text
simple-website-examples
```

So the final published model is:

```text
18 website-code example repos
1 hub documentation repo
```

---

## Who This Is For

This series is useful for:

- Beginners learning web development from scratch
- Developers who want small reference examples without framework complexity
- Teachers or mentors who want incremental examples
- Anyone who wants to compare simple HTML/CSS/JavaScript patterns across focused examples

---

## How to Use This Series

Recommended path:

1. Start with Example 01.
2. Move forward in order through Example 18.
3. Use the hub documentation when you want broader context, terminology, repo naming history, or file-structure explanations.
4. Use source-reference material when you want preserved background material from earlier project packaging.

You can also jump directly to a specific example if you want a focused demonstration of one topic.

---

## Learning Progression

| Phase | Examples | Focus |
|---|---:|---|
| Foundations | 01-03 | Basic HTML, site files, CSS, JavaScript, and assets |
| Multi-page structure | 04-05 | Multiple pages, navigation, organization, and maintainability |
| Forms and input | 06-07 | Basic forms, JavaScript feedback, and validation |
| Images, layout, metadata | 08-10 | Images, responsive layout, metadata, favicons, and head content |
| Accessibility and usability | 11-12 | Labels, alt text, meaningful links, navigation, focus states, and usability |
| Metadata and JavaScript organization | 13-14 | Open Graph, robots metadata, social preview assets, and organized JavaScript |
| Refinements and media | 15-18 | Expanded form controls, accessibility refinements, responsive refinements, audio, video, and embeds |

---

## Example Summary

| # | Example | Repo name | Demonstrates |
|---:|---|---|---|
| 01 | First Web Page | `simple-website-01-first-web-page` | A single minimal HTML page and the basic shape of an HTML document. |
| 02 | Basic Site Files | `simple-website-02-basic-site-files` | Basic site completeness with `index.html`, `robots.txt`, and `sitemap.xml`. |
| 03 | HTML, CSS, and JavaScript Assets | `simple-website-03-html-css-js-assets` | Separating structure, style, and behavior into HTML, CSS, and JavaScript files. |
| 04 | Multi-Page Site | `simple-website-04-multi-page-site` | Multiple pages, navigation, shared CSS, and a 404 page. |
| 05 | Maintainable File Structure | `simple-website-05-maintainable-file-structure` | Organized CSS files and maintainable static-site structure. |
| 06 | Basic Forms | `simple-website-06-basic-forms` | Labeled form inputs, submission handling, and basic JavaScript feedback. |
| 07 | Form Validation | `simple-website-07-form-validation` | Client-side form validation, multiple fields, error messages, and user feedback. |
| 08 | Images and Gallery | `simple-website-08-images-and-gallery` | Image assets, a gallery page, captions, and simple image-focused layout. |
| 09 | Responsive Layout Basics | `simple-website-09-responsive-layout-basics` | Mobile-friendly layout changes with plain CSS. |
| 10 | Head Metadata and Favicon | `simple-website-10-head-metadata-and-favicon` | Metadata, meta descriptions, supporting pages, and favicon setup. |
| 11 | Accessibility Basics | `simple-website-11-accessibility-basics` | Labels, alt text, meaningful structure, clearer links, and readable content. |
| 12 | Navigation and Usability | `simple-website-12-navigation-and-usability` | Consistent navigation, active/focus states, and clearer user flow. |
| 13 | Open Graph and Metadata | `simple-website-13-open-graph-and-metadata` | Open Graph tags, robots metadata, author metadata, favicons, and social preview imagery. |
| 14 | JavaScript Organization | `simple-website-14-javascript-organization` | Dedicated JavaScript files, event handling, helper functions, and readable structure. |
| 15 | Expanded Form Controls | `simple-website-15-expanded-form-controls` | Textareas, selects, checkboxes, radio buttons, and additional form controls. |
| 16 | Accessibility Refinements | `simple-website-16-accessibility-refinements` | Skip links, improved focus styling, labeled input, and refined accessibility patterns. |
| 17 | Responsive Layout Refinements | `simple-website-17-responsive-layout-refinements` | Additional breakpoints, improved layout behavior, and responsive refinements. |
| 18 | Media and Embeds | `simple-website-18-media-and-embeds` | Audio, video, embedded content, figure captions, and supporting media assets. |

---

## File Structure Progression

The examples gradually introduce new files and folders.

### Example 01

```text
index.html
```

### Example 02

```text
index.html
robots.txt
sitemap.xml
```

### Example 03

```text
404.html
index.html
assets/
  css/
    styles.css
  js/
    script.js
```

### Example 04

```text
404.html
about.html
index.html
assets/
  css/
    styles.css
```

### Example 05

```text
404.html
about.html
index.html
assets/
  css/
    about.css
    common.css
    error.css
    home.css
```

### Example 06

```text
404.html
index.html
assets/
  css/
    styles.css
  js/
    script.js
```

### Example 07

```text
404.html
index.html
assets/
  css/
    styles.css
  js/
    script.js
```

### Example 08

```text
404.html
gallery.html
index.html
assets/
  css/
    styles.css
  images/
    sample-photo.svg
```

### Example 09

```text
404.html
index.html
assets/
  css/
    styles.css
```

### Example 10

```text
404.html
about.html
index.html
assets/
  css/
    styles.css
  images/
    favicon.svg
```

### Example 11

```text
404.html
about.html
index.html
assets/
  css/
    styles.css
  images/
    sample.svg
```

### Example 12

```text
404.html
about.html
contact.html
index.html
assets/
  css/
    styles.css
```

### Example 13

```text
404.html
about.html
index.html
assets/
  css/
    styles.css
  images/
    favicon.png
    favicon.svg
    share-preview.svg
```

### Example 14

```text
404.html
about.html
index.html
assets/
  css/
    styles.css
  js/
    script.js
```

### Example 15

```text
index.html
assets/
  css/
    styles.css
```

### Example 16

```text
index.html
sample.svg
assets/
  css/
    styles.css
```

### Example 17

```text
404.html
about.html
index.html
assets/
  css/
    styles.css
```

### Example 18

```text
404.html
about.html
embed-example.html
index.html
assets/
  css/
    styles.css
  media/
    sample-audio.mp3
    sample-video.mp4
```

---

## Related Active Documentation

The active current documentation is in the hub repo:

```text
README.md
CHANGELOG.md
docs/learning-path.md
docs/project-summary.md
docs/file-structure-reference.md
docs/glossary.md
docs/repository-linking.md
docs/repository-descriptions.md
docs/naming-history.md
docs/templates/README-template.md
```

Use those files as the primary current docs.

---

## Archived Source Material

The files used to create this curated source-reference file are preserved under:

```text
docs/source-reference/archive/series-reference-sources/
```

Original Project 19 source files are preserved under:

```text
docs/source-reference/archive/original-project-19/
```

They are retained for historical/reference purposes and should not be treated as the primary current documentation.

---

## Notes

- The series is intentionally simple.
- The examples are static website examples, not full production application templates.
- Website source code for Examples 01 through 18 is not changed by this hub documentation cleanup.
- The documentation hub preserves earlier source-reference material without keeping every older file in the main source-reference folder.

# Simple Website Examples

A progressive series of plain HTML, CSS, and JavaScript examples that build from the smallest possible web page to more complete static website patterns.

This hub repository organizes the full learning series. The website examples themselves are intended to live in separate GitHub repositories, with this hub README linking to each standalone example repo.

## Recommended repository layout

GitHub owner: `jefsko`

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

## Naming and version history

This `v1.1.0` repo set uses the final recommended GitHub repository names.

Earlier development snapshots used different folder/repo names:

| Version stage | Naming pattern | Notes |
|---|---|---|
| `v0.2.0` pre-production snapshot | `project-N-topic` | Early development folder names. |
| `v1.0.0` production snapshot | `simple-website-N-topic` | First production-style names, but not yet zero-padded/finalized. |
| `v1.1.0` documentation/naming update | `simple-website-##-topic` | Final website example repo names with zero-padded numbers and clearer topic labels. |
| `v1.1.0` hub update | `simple-website-examples` | The former documentation-only Project 19 content is now the hub repo instead of a website example repo. |

The rename history is documented for transparency because these versions are being reconstructed and checked into Git after development. The final `v1.1.0` names are the recommended names to use going forward.

See also: [Naming history](docs/naming-history.md)

## Website examples

| # | Example | Recommended repo name | Focus |
|---:|---|---|---|
| 01 | [First Web Page](https://github.com/jefsko/simple-website-01-first-web-page) | `simple-website-01-first-web-page` | A single minimal HTML page that shows the basic shape of an HTML document. |
| 02 | [Basic Site Files](https://github.com/jefsko/simple-website-02-basic-site-files) | `simple-website-02-basic-site-files` | A minimal website setup that adds UTF-8 metadata, robots.txt, and sitemap.xml around a basic page. |
| 03 | [HTML, CSS, and JavaScript Assets](https://github.com/jefsko/simple-website-03-html-css-js-assets) | `simple-website-03-html-css-js-assets` | A basic static website example that separates HTML, CSS, and JavaScript into dedicated files. |
| 04 | [Multi-Page Site](https://github.com/jefsko/simple-website-04-multi-page-site) | `simple-website-04-multi-page-site` | A simple multi-page static website with home/about pages, navigation, shared CSS, and a 404 page. |
| 05 | [Maintainable File Structure](https://github.com/jefsko/simple-website-05-maintainable-file-structure) | `simple-website-05-maintainable-file-structure` | A maintainability-focused static site showing organized CSS files and a clearer project structure. |
| 06 | [Basic Forms](https://github.com/jefsko/simple-website-06-basic-forms) | `simple-website-06-basic-forms` | A simple form example showing labels, inputs, submission handling, and basic JavaScript feedback. |
| 07 | [Form Validation](https://github.com/jefsko/simple-website-07-form-validation) | `simple-website-07-form-validation` | A form validation example with multiple input types, client-side checks, and user feedback. |
| 08 | [Images and Gallery](https://github.com/jefsko/simple-website-08-images-and-gallery) | `simple-website-08-images-and-gallery` | An image-focused static site with a gallery page and organized image assets. |
| 09 | [Responsive Layout Basics](https://github.com/jefsko/simple-website-09-responsive-layout-basics) | `simple-website-09-responsive-layout-basics` | A responsive design starter showing mobile-friendly layout changes with plain CSS. |
| 10 | [Head Metadata and Favicon](https://github.com/jefsko/simple-website-10-head-metadata-and-favicon) | `simple-website-10-head-metadata-and-favicon` | A metadata-focused static site demonstrating head tags, meta descriptions, and favicon setup. |
| 11 | [Accessibility Basics](https://github.com/jefsko/simple-website-11-accessibility-basics) | `simple-website-11-accessibility-basics` | An accessibility basics example showing labels, alt text, meaningful structure, and clearer content. |
| 12 | [Navigation and Usability](https://github.com/jefsko/simple-website-12-navigation-and-usability) | `simple-website-12-navigation-and-usability` | A navigation and usability example with consistent pages, active/focus states, and clearer user flow. |
| 13 | [Open Graph and Metadata](https://github.com/jefsko/simple-website-13-open-graph-and-metadata) | `simple-website-13-open-graph-and-metadata` | An advanced metadata example with Open Graph tags, robots directives, author metadata, and favicons. |
| 14 | [JavaScript Organization](https://github.com/jefsko/simple-website-14-javascript-organization) | `simple-website-14-javascript-organization` | A JavaScript organization example using a dedicated script file, event handling, and readable functions. |
| 15 | [Expanded Form Controls](https://github.com/jefsko/simple-website-15-expanded-form-controls) | `simple-website-15-expanded-form-controls` | An expanded forms example covering textareas, selects, checkboxes, radio buttons, and form layout. |
| 16 | [Accessibility Refinements](https://github.com/jefsko/simple-website-16-accessibility-refinements) | `simple-website-16-accessibility-refinements` | An accessibility refinement example with skip links, focus styling, and more deliberate accessibility patterns. |
| 17 | [Responsive Layout Refinements](https://github.com/jefsko/simple-website-17-responsive-layout-refinements) | `simple-website-17-responsive-layout-refinements` | A responsive refinement example with multiple breakpoints and more polished layout behavior. |
| 18 | [Media and Embeds](https://github.com/jefsko/simple-website-18-media-and-embeds) | `simple-website-18-media-and-embeds` | A media and embeds example showing audio, video, figure captions, and embedded content. |

## Documentation

- [Learning path](docs/learning-path.md)
- [Project summary](docs/project-summary.md)
- [File structure reference](docs/file-structure-reference.md)
- [Glossary](docs/glossary.md)
- [Repository linking strategy](docs/repository-linking.md)
- [Repository descriptions](docs/repository-descriptions.md)
- [Naming history](docs/naming-history.md)
- [Source reference documents](docs/source-reference/README.md)
- [Series reference](docs/source-reference/series-reference.md)
- [README template](docs/templates/README-template.md)

## Why the hub plus separate example repos?

The hub keeps the whole series easy to discover, while separate example repos keep each website small, focused, cloneable, and releasable on its own.

This avoids turning one repository into a mixed archive of unrelated stages, while still preserving the full sequence through README links and shared documentation.

## How to use this series

1. Start with [Example 01 — First Web Page](https://github.com/jefsko/simple-website-01-first-web-page).
2. Move forward in order through [Example 18 — Media and Embeds](https://github.com/jefsko/simple-website-18-media-and-embeds).
3. Use the hub documentation when you want the broader context, terminology, or file-structure explanations.

## What this series covers

- Minimum useful website files
- Core HTML structure
- CSS styling
- JavaScript behavior
- Multi-page navigation
- Forms and validation
- Images and media
- Responsive layout
- Metadata
- Accessibility
- Repository documentation

## What this series does not cover

- Frameworks such as React, Vue, Angular, or Svelte
- Backend development
- Databases
- Package managers
- Build tools
- Deployment automation
- Advanced SEO

## Version

Current hub version: `v1.1.2`

The initial organized hub documentation started at `v1.0.0`. Patch versions `v1.0.1` through `v1.0.3` preserved source-reference documents and refined the full project reference. Version `v1.1.0` is a documentation and repository-packaging update that adopts the shorter `simple-website-##-topic` repo naming pattern, adds naming-history documentation, updates cross-repo GitHub links, and keeps the source-reference material synchronized with the latest `v1.0.3` documentation. Version `v1.1.1` is a cleanup update that moves the reusable README template into `docs/templates/` and normalizes Markdown line endings. Version `v1.1.2` consolidates overlapping source-reference material into `docs/source-reference/series-reference.md` and archives the older source-reference inputs and original Project 19 files for traceability.
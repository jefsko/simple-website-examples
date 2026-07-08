# Naming History

This document records the repository/folder naming evolution for the Simple Website Examples project.

## Why this exists

The project was developed through several pre-production and production snapshots before the final v1.1.0 repository layout was prepared for GitHub. Because the versions are being reconstructed and checked into Git after development, this naming history is documented here for transparency.

## Version-stage summary

| Version stage | Naming pattern | Purpose |
|---|---|---|
| `v0.2.0` pre-production snapshot | `project-N-topic` | Early development folder names used while the examples were still being assembled. |
| `v1.0.0` production snapshot | `simple-website-N-topic` | First production-oriented naming pass. |
| `v1.1.0` naming/documentation update | `simple-website-##-topic` | Final website example repo names using zero-padded numbers and clearer topic labels. |
| `v1.1.0` hub consolidation | `simple-website-examples` | Former Project 19 documentation became the hub repo instead of a website-code example. |

## v1.0.0 to v1.1.0 repository-name mapping

| # | v1.0.0 name | v1.1.0 final name | Topic |
|---:|---|---|---|
| 01 | `simple-website-1-first-web-page` | `simple-website-01-first-web-page` | First Web Page |
| 02 | `simple-website-2-basic-website-setup` | `simple-website-02-basic-site-files` | Basic Site Files |
| 03 | `simple-website-3-basic-website-assets` | `simple-website-03-html-css-js-assets` | HTML, CSS, and JavaScript Assets |
| 04 | `simple-website-4-multi-page-website` | `simple-website-04-multi-page-site` | Multi-Page Site |
| 05 | `simple-website-5-website-maintenance-basics` | `simple-website-05-maintainable-file-structure` | Maintainable File Structure |
| 06 | `simple-website-6-user-input-and-forms` | `simple-website-06-basic-forms` | Basic Forms |
| 07 | `simple-website-7-advanced-forms-and-validation` | `simple-website-07-form-validation` | Form Validation |
| 08 | `simple-website-8-images-and-media` | `simple-website-08-images-and-gallery` | Images and Gallery |
| 09 | `simple-website-9-responsive-design-basics` | `simple-website-09-responsive-layout-basics` | Responsive Layout Basics |
| 10 | `simple-website-10-head-and-metadata` | `simple-website-10-head-metadata-and-favicon` | Head Metadata and Favicon |
| 11 | `simple-website-11-accessibility-basics` | `simple-website-11-accessibility-basics` | Accessibility Basics |
| 12 | `simple-website-12-navigation-and-usability` | `simple-website-12-navigation-and-usability` | Navigation and Usability |
| 13 | `simple-website-13-advanced-head-and-metadata` | `simple-website-13-open-graph-and-metadata` | Open Graph and Metadata |
| 14 | `simple-website-14-javascript-organization-basics` | `simple-website-14-javascript-organization` | JavaScript Organization |
| 15 | `simple-website-15-expanded-forms` | `simple-website-15-expanded-form-controls` | Expanded Form Controls |
| 16 | `simple-website-16-accessibility-refinements` | `simple-website-16-accessibility-refinements` | Accessibility Refinements |
| 17 | `simple-website-17-responsive-design-refinements` | `simple-website-17-responsive-layout-refinements` | Responsive Layout Refinements |
| 18 | `simple-website-18-media-and-embeds` | `simple-website-18-media-and-embeds` | Media and Embeds |

## Project 19 / hub change

In earlier snapshots, the documentation companion appeared as a numbered Project 19 folder:

```text
project-19-project-documentation
simple-website-19-project-documentation
```

In v1.1.0, that documentation-only content is incorporated into the hub repository:

```text
simple-website-examples
```

This keeps the series clearer:

- Examples 01 through 18 are the website-code examples.
- `simple-website-examples` is the hub and documentation index.
- There is no v1.1.0 website-code repo named `simple-website-19-project-documentation`.

## Should this be documented in every repo?

Only lightly.

The hub documents the full naming transition because it explains the entire series. Individual example repos document their own v1.1.0 name update in `CHANGELOG.md`, but their `README.md` files stay focused on the current final repo names and learning content.

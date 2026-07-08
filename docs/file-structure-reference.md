# File Structure Reference

This reference explains common files and folders used throughout the Simple Website Examples series.

## Common static website structure

```text
index.html
about.html
404.html
assets/
  css/
    styles.css
  js/
    script.js
  images/
  media/
README.md
CHANGELOG.md
```

## Common file roles

| File or folder | Role | Required? |
|---|---|---|
| `index.html` | Default home page for the site. | Usually yes for a basic static site. |
| `about.html` | Optional secondary page. | Optional. |
| `404.html` | Custom not-found page for static hosting. | Optional, but conventional. |
| `assets/` | Folder for supporting files. | Optional, but recommended once supporting files exist. |
| `assets/css/` | Stylesheets. | Optional until CSS is needed. |
| `assets/js/` | JavaScript files. | Optional until JavaScript is needed. |
| `assets/images/` | Image files. | Optional until images are needed. |
| `assets/media/` | Audio and video files. | Optional until media is needed. |
| `robots.txt` | Search crawler instructions. | Optional. |
| `sitemap.xml` | List of important site URLs for search engines. | Optional. |
| `README.md` | Repository explanation. | Not required by the browser, but strongly recommended. |
| `CHANGELOG.md` | Version history. | Not required by the browser, but recommended. |

## Naming conventions

Use lowercase names, hyphens between words, and no spaces. Examples:

```text
index.html
about.html
styles.css
script.js
sample-photo.svg
simple-website-01-first-web-page
```

## Required vs. optional

A browser can open a single `index.html` file. Everything else is added as the project needs more structure, styling, behavior, media, metadata, documentation, or hosting support.

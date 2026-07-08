# Repository Linking Strategy

The recommended linking method for this project is simple README linking using true GitHub cross-repo URLs.

## Naming history and final link targets

This `v1.1.0` documentation uses the final repository names.

Earlier snapshots used different local folder/repo names while the project was still being organized:

| Stage | Pattern | Example |
|---|---|---|
| Early pre-production | `project-N-topic` | `project-2-basic-website-setup` |
| First production snapshot | `simple-website-N-topic` | `simple-website-2-basic-website-setup` |
| Final `v1.1.0` naming | `simple-website-##-topic` | `simple-website-02-basic-site-files` |

The `v1.1.0` package also treats the former documentation-only Project 19 folder, `simple-website-19-project-documentation`, as the hub repository `simple-website-examples`.

Because these folders are intended to become separate GitHub repositories, cross-repo navigation should use the final GitHub URLs, not local sibling-folder links.

## Recommended approach

Use one hub repository plus one separate repository for each website example:

```text
simple-website-examples
simple-website-01-first-web-page
simple-website-02-basic-site-files
...
simple-website-18-media-and-embeds
```

The hub README should link to each example using its final GitHub URL. Each example README should link back to the hub and to the previous and next examples using the same cross-repo URL style.

## Why README links are best here

README links are simple, visible, beginner-friendly, and do not require special Git commands. They let each example remain a normal standalone repository.

## Ranking

| Rank | Method | Recommendation | Why |
|---:|---|---|---|
| 1 | README links | Best | Simple, clear, visible, and easy to maintain. |
| 2 | GitHub topics | Good supplement | Helps discovery and grouping, but does not create direct navigation. |
| 3 | GitHub About/homepage link | Good supplement | Useful metadata, but less visible than README links. |
| 4 | Git submodules | Avoid for this project | Powerful, but adds clone/update complexity. |
| 5 | Git subtree | Avoid for this project | Useful in advanced repo management, but unnecessary here. |

## Link style used in this package

This packaged file set uses true GitHub cross-repo links for navigation between the hub and example repositories. This is intentional because each folder is intended to become its own separate repository under `jefsko`.

Use relative links only for files inside the same repository, such as `CHANGELOG.md` or files under `docs/`. Use absolute GitHub links for links from one repo to another repo.

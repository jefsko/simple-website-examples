# Changelog

All notable changes to the Simple Website Examples hub are documented in this file.

This project follows semantic-style version numbers such as `v1.0.0`.

## [1.1.1] - 2026-07-08

### Changed
- Moved the reusable README template from `docs/source-reference/` to `docs/templates/`.
- Updated documentation references to point to the README template's new location.
- Normalized remaining Markdown files to Windows CRLF line endings for consistency.

## [1.1.0] - 2026-07-07

### Added
- Added repository linking guidance under `docs/repository-linking.md`.
- Added GitHub repository description guidance under `docs/repository-descriptions.md`.
- Added naming-history documentation under `docs/naming-history.md`.
- Added preserved original Project 19 documentation files under `docs/source-reference/` with `original-project-19-` filenames.
- Added a source-reference index under `docs/source-reference/README.md`.

### Changed
- Standardized the final published repository naming pattern to `simple-website-##-topic`, using zero-padded example numbers for predictable sorting.
- Updated recommended website example repository names from `simple-website-example-##-topic` to `simple-website-##-topic` for shorter, simpler repo names.
- Updated cross-repo README links to use the simplified final GitHub repository names under `jefsko`.
- Reorganized the active supporting documentation under `docs/` while keeping the root focused on `README.md` and `CHANGELOG.md`.
- Carried forward the latest `v1.0.3` full project reference under `docs/source-reference/full-project-reference.md`.
- Kept the unversioned `full-project-reference.md` filename for the source-reference document.

### Reorganized
- Treated the former documentation-only Project 19 repository/folder, `simple-website-19-project-documentation`, as the series hub repository: `simple-website-examples`.
- Kept Examples 01 through 18 as the website-code examples and kept the former Project 19 documentation content inside the hub under `docs/` and `docs/source-reference/`.

### Historical naming note
- Earlier pre-production snapshots used the `project-N-topic` folder pattern.
- The `v1.0.0` production snapshot moved to the `simple-website-N-topic` pattern.
- The `v1.1.0` update finalized the zero-padded `simple-website-##-topic` pattern for the website examples and made `simple-website-examples` the hub repository.
- The naming history is documented in `docs/naming-history.md`.

### Notes
- Examples 01 through 18 remain the website-code examples.
- Website source code for Examples 01 through 18 is not intentionally changed by this repository naming/documentation update.
- The former Project 19 documentation remains incorporated into this hub repository as documentation and preserved source-reference material.
- Some source-reference documents overlap conceptually with active documentation, but they are retained for now rather than merged so no prior reference material is lost.

## [1.0.3] - 2026-07-07

### Changed
- Refined `docs/source-reference/full-project-reference.md` by combining the clearer summary wording from the updated reference file with the more detailed project descriptions from the existing version.
- Standardized the project summary formatting so each project uses a consistent `Builds on:` section.

## [1.0.2] - 2026-07-07

### Fixed
- Corrected the source-reference index to point to `full-project-reference.md`.

## [1.0.1] - 2026-07-07

### Added
- Added preserved source reference documents under `docs/source-reference/`.
- Added an index for the imported source reference documents.
- Added earlier project-set root reference material so the information is retained in the documentation repo.

### Changed
- Updated the README to point to the preserved source reference documents.

## [1.0.0] - Initial production-ready documentation snapshot

### Added
- Added the initial documentation repo for the Simple Website Examples project.
- Added the series README, learning path, glossary, file structure reference, and project summary.

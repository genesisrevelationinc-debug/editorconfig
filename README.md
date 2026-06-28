### This repository is placeholder used for [issue tracking][] for format issues and other universal [EditorConfig][] issues, as well as the [wiki pages][].

## New Properties for File Exclusion

This repository now includes proposed properties for excluding files from listings and search indexing:

| Property | Description |
|----------|-------------|
| `file_exclude_patterns` | Comma-separated list of file patterns to exclude from file listings (e.g., folder tree panes). Analogous to Sublime Text's `file_exclude_patterns`. |
| `folder_exclude_patterns` | Comma-separated list of folder patterns to exclude from file listings. Analogous to Sublime Text's `folder_exclude_patterns`. |
| `index_exclude_patterns` | Comma-separated list of file patterns to exclude from search indexing. Analogous to Sublime Text's `index_exclude_patterns`. |
| `exclude_from_listing` | Boolean indicating whether matched files should be excluded from file listings. |
| `exclude_from_index` | Boolean indicating whether matched files should be excluded from search indexing. |

### Example Usage



[EditorConfig]: https://editorconfig.org
[issue tracking]: https://github.com/editorconfig/editorconfig/issues
[wiki pages]: https://github.com/editorconfig/editorconfig/wiki

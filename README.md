### This repository is placeholder used for [issue tracking][] for format issues and other universal [EditorConfig][] issues, as well as the [wiki pages][].


[EditorConfig]: https://editorconfig.org
[EditorConfig]: https://editorconfig.org
[issue tracking]: https://github.com/editorconfig/editorconfig/issues
[wiki pages]: https://github.com/editorconfig/editorconfig/wiki

## New Properties for File Exclusion

This repository now supports two new properties for controlling file visibility and search indexing:

- `file_exclude_patterns`: When set to `true`, indicates that files matching the pattern should not be displayed in file listings (e.g., folder tree panes).
- `index_exclude_patterns`: When set to `true`, indicates that files matching the pattern should not be indexed for search or displayed in search results.

### Example Usage



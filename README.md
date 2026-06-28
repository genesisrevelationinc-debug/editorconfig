### This repository is placeholder used for [issue tracking][] for format issues and other universal [EditorConfig][] issues, as well as the [wiki pages][].


[EditorConfig]: https://editorconfig.org
[issue tracking]: https://github.com/editorconfig/editorconfig/issues
### This repository is placeholder used for [issue tracking][] for format issues and other universal [EditorConfig][] issues, as well as the [wiki pages][].


[EditorConfig]: https://editorconfig.org
[issue tracking]: https://github.com/editorconfig/editorconfig/issues
[wiki pages]: https://github.com/editorconfig/editorconfig/wiki

## New Properties for File Exclusion

This repository now supports three new properties for controlling file visibility and search indexing:

- `file_exclude_patterns`: Comma-separated list of file patterns to exclude from file listings (e.g., `.git, .DS_Store, Thumbs.db`)
- `folder_exclude_patterns`: Comma-separated list of folder patterns to exclude from file listings (e.g., `.git, node_modules, __pycache__`)
- `index_exclude_patterns`: Comma-separated list of file patterns to exclude from search indexing (e.g., `*.log, *.tmp, build/*`)

These properties are analogous to Sublime Text's `file_exclude_patterns`, `folder_exclude_patterns`, and `index_exclude_patterns`.

### Example Usage


[wiki pages]: https://github.com/editorconfig/editorconfig/wiki

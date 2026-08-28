# Awesome Diff Tools with stars

A collaborative list of great tools that show differences between files and folders. Feel free to contribute to this list.

## Contents

* [Source Code](#source-code)
  * [Standard Tools](#standard-tools)
  * [Semantic Diffs](#semantic-diffs)
  * [Diff Enhancers](#diff-enhancers)
* [Other Text Formats](#other-text-formats)
* [Databases](#databases)
* [PDF](#pdf)
* [Binary Data](#binary-data)
* [Folder Comparison](#folder-comparison)

## Source Code

### Standard Tools

The most commonly used tools to display changes between two versions of a source code.

* [GNU Diffutils](https://www.gnu.org/software/diffutils/) - Popular set of tools to compute unified diffs between files, supports two-way and three-way diffs.
* [git (diff)](https://git-scm.com/) - Popular version control system, can compute unified diffs between commits, workings trees, branches, etc.

### Semantic Diffs

Programming language aware diffs that provide additional features like hiding syntax-only changes.

* [difftastic](https://github.com/Wilfred/difftastic) ⭐ 25,826 | 🐛 298 | 🌐 Rust | 📅 2026-08-27 - Terminal utility to generate side-by-side diffs, hides style changes and supports many languages, but doesn't detect moved code.
* [diffsitter](https://github.com/afnanenayet/diffsitter) ⭐ 2,395 | 🐛 34 | 🌐 Rust | 📅 2026-08-27 - Terminal utility to generate unified diffs, hides style changes, but doesn't detect moved code.
* [gumtree](https://github.com/GumTreeDiff/gumtree) ⭐ 1,334 | 🐛 22 | 🌐 Java | 📅 2026-08-25 - Web/GUI/Text frontend to generate side-by-side diffs, hides style changes and detects moved code.
* [zograscope](https://github.com/xaizek/zograscope) ⭐ 56 | 🐛 1 | 🌐 C++ | 📅 2026-03-21 - Terminal utility to generate side-by-side diffs, hides style changes, mostly focused on C/C++.
* [SemanticDiff](https://semanticdiff.com) - VS Code extension/GitHub App to generate side-by-side diffs, hides style changes, detects moved code blocks and simple refactorings.

### Diff Enhancers

Wrappers that enhance the output of an existing diff tool.

* [delta](https://github.com/dandavison/delta) ⭐ 31,885 | 🐛 429 | 🌐 Rust | 📅 2026-08-02 - Pager for (git) diff, adds syntax highlighting, inline and side-by-side view, support for git blame and merge conflicts.
* [diff-so-fancy](https://github.com/so-fancy/diff-so-fancy) ⭐ 18,082 | 🐛 4 | 🌐 Perl | 📅 2026-08-19 - Pager for (git) diff, changes colors and highlights inline changes, various options to customize output format.
* [icdiff](https://github.com/jeffkaufman/icdiff) ⭐ 4,388 | 🐛 25 | 🌐 Python | 📅 2026-02-08 - Standalone application for side-by-side diffs with syntax highlighting.
* [git-split-diffs](https://github.com/banga/git-split-diffs) ⭐ 2,745 | 🐛 12 | 🌐 TypeScript | 📅 2026-08-20 - Pager for (git) diff, displays changes like GitHub split diffs (side-by-side diffs) with syntax highlighting.
* [ydiff](https://github.com/ymattw/ydiff) ⭐ 931 | 🐛 2 | 🌐 Python | 📅 2026-05-20 - Pager for git diff, supports unified and side-by-side view, highlights inline changes.
* [dunk](https://github.com/darrenburns/dunk) ⭐ 889 | 🐛 22 | 🌐 Python | 📅 2025-04-19 - Postprocesses the output of git diff to generate side-by-side diffs, supports syntax highlighting and highlights inline changes.
* [diffr](https://github.com/mookid/diffr) ⭐ 613 | 🐛 14 | 🌐 Rust | 📅 2026-01-08 - Pager for git diff, changes colors and highlights inline changes.
* [riff](https://github.com/walles/riff) ⭐ 524 | 🐛 4 | 🌐 Rust | 📅 2026-08-15 - Wrapper around (`git`) `diff` highlighting which parts of lines that changed.

## Other Text Formats

Diff utilities for non-code based text formats.

* [Graphtage](https://github.com/trailofbits/graphtage) ⭐ 2,477 | 🐛 29 | 🌐 Python | 📅 2026-08-04 - Semantic diff for JSON, JSON5, XML, HTML, YAML, CSV.
* [jd](https://github.com/josephburnett/jd) ⭐ 2,297 | 🐛 20 | 🌐 Go | 📅 2026-04-22 - Creates diffs for JSON/YAML files, also supports patching.
* [dyff](https://github.com/homeport/dyff) ⭐ 1,878 | 🐛 69 | 🌐 Go | 📅 2026-08-17 - Pager for git diff (or standalone) for YAML/JSON, enhances display of changes and their location.
* [OpenAPI-diff](https://github.com/OpenAPITools/openapi-diff) ⭐ 1,096 | 🐛 82 | 🌐 Java | 📅 2026-08-27 - Utility for comparing two OpenAPI specifications.
* [xcdiff](https://github.com/bloomberg/xcdiff) ⭐ 961 | 🐛 10 | 🌐 Swift | 📅 2026-03-08 - Terminal utility to find differences between two .xcodeproj project files.
* [daff](https://github.com/paulfitz/daff) ⭐ 923 | 🐛 47 | 🌐 Java | 📅 2026-05-27 - Library for comparing tables format such as csv files.
* [prettier-diff](https://github.com/josephfrazier/prettier-diff) ⭐ 36 | 🐛 4 | 🌐 JavaScript | 📅 2026-08-12 - Wrapper around git diff for JavaScript/JSON, preprocesses the data with a prettifier.
* [JSON Diff](https://www.jsondiff.com/) - Online tool to compute a semantic diff for JSON files.
* [nbdime](https://nbdime.readthedocs.io/en/latest/) - Diffing and merging of Jupyter Notebooks.

## Databases

Diff utilities to compare the schema or content of databases.

* [migra](https://github.com/djrobstep/migra) ⭐ 3,050 | 🐛 88 | 🌐 Python | 📅 2025-08-25 - Compares the schema of PostgreSQL databases and generates migrations.
* [Another PostgreSQL Diff Tool](https://github.com/fordfrog/apgdiff) ⭐ 378 | 🐛 129 | 🌐 Java | 📅 2024-01-03 - Compares the schema of PostgreSQL dumps.

## PDF

Diff utilities to compare the content of PDF files.

* [diff-pdf](https://vslavik.github.io/diff-pdf/) - Generates a PDF file with visually highlighted differences based on the input PDFs.
* [DiffPDF](https://www.qtrac.eu/diffpdf.html) - Interactive GUI for comparing two PDF files.

## Binary Data

Diff utilities to compare binary data.

* [diffuse](https://github.com/JakeWharton/diffuse) ⭐ 2,185 | 🐛 27 | 🌐 Kotlin | 📅 2026-08-27 - Compares the content of APKs, AABs, AARs, and JARs.
* [multidiff](https://github.com/juhakivekas/multidiff) ⭐ 309 | 🐛 5 | 🌐 Python | 📅 2023-02-12 - Utility to diff multiple binary objects or streams of data.
* [VBinDiff](https://www.cjmweb.net/vbindiff/) - Side by side comparison of binary data in hex and ascii format.

## Folder Comparison

Diff utilities that can compare the content of whole directories.

* [WinMerge](https://winmerge.org) - Supports code (with syntax highlighting), text, image and CSV files.
* [Meld](https://meldmerge.org/) - Supports text based files, also integrates with version control systems.

## Contributing

Contributing is greatly welcomed! Please read the [Contribution Guidelines](Contributing.md) before taking any action.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-28._

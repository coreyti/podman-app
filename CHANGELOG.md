---
head: Bootstrap part 2
---

# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/), and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added

- The project
- [`vendir`](https://carvel.dev/vendir/) is introduced to manage dependencies and references with `${WORKSPACE}/lib`.
- `ergo-bundle` now runs `vendir sync`. This likely should be relocated to `ergonomic`.
- `ws-sync` wraps `ergo-bundle` and adds workspace-specific sync/installation.
- `podman` is managed via `vendir` (mainly because the current `brew` version is not an **exact** match for the server version).

### Updated

- Hopefully, the change content to reflect this project's changes, rather than those of the parent [`ergonomic`](https://github.com/coreyti/ergonomic) workspace.

### Footnotes

- ...

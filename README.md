# PageBrick catalog

The list every PageBrick site reads to find updates of PageBrick itself, and plugins and themes to install from the panel.

- `catalog.json` follows format 1, described in [docs/en/publishing.md](https://github.com/PageBrick/pagebrick/blob/main/docs/en/publishing.md).
- Every package is signed with the project's Ed25519 key. Sites install only what that signature covers (type, name, version and the file's SHA-256), so a changed file or a fake version is refused even if this list is edited.
- The signature guarantees that a file is the one the maintainers published. It is not a code review: install only what you trust.

To propose a plugin or theme, open an issue with a link to its source code.

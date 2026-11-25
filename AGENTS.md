# orfo-brand

Shared rules: ORFO's [conventions](https://github.com/OrfoBe/orfo/blob/main/docs/conventions.md); which repository holds what: the [map](https://github.com/OrfoBe/orfo/blob/main/docs/map.md).

`orfo-brand` is public: it holds the logos that email signatures and sites load from jsDelivr, `https://cdn.jsdelivr.net/gh/OrfoBe/orfo-brand@main/<file>`. The charter that rules them, and the signatures that use them, are in `orfo-web` (`docs/identite-visuelle.md`, `email-signatures/`).

| Path | What |
| --- | --- |
| `*.png` at the root | The files served; the [README](README.md) says which brand, background and use each has |
| `exports/` | The charter's full set of logo exports, under their design names; a source, not served |

## Rules

- Everything here is public: only assets meant to be published, never a person's file, an address or a draft.
- A served file is never renamed or deleted: live signatures load it by its name at `@main`. A new version keeps the name, or comes under a new name next to the old one.
- A signature logo is made by `orfo-web`'s `email-signatures/scripts/make-logo.js`, then published here with the same file.
- Logos are exported at twice their size and shown at half.

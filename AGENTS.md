# orfo-brand

Shared rules: ORFO's [conventions](https://github.com/OrfoBe/orfo/blob/main/docs/conventions.md); which repository holds what: the [map](https://github.com/OrfoBe/orfo/blob/main/docs/map.md).

`orfo-brand` is public: jsDelivr serves its files at `https://cdn.jsdelivr.net/gh/OrfoBe/orfo-brand@main/<file>`. The charter that rules them is in `orfo-web` (`docs/identite-visuelle.md`).

| Path | What |
| --- | --- |
| `*.png` at the root | The files pages load; the [README](README.md) says which brand, background and use each has |
| `exports/` | The charter's full set of logo masters, under their design names: a source no live page loads |

They are loaded by name at `@main`:

| Repository | Where | File |
| --- | --- | --- |
| `orfo-web` | `email-signatures/`, the Gmail signatures | `*-signature.png` and the generic logos |
| `orfo-apps-script` | `plan-configurateur/`, `graphisme-configurateur/` | `orfo-studio-blanc.png` |
| `orfo-platform` | `templates/rentman/` | `orfo-studio-logo.png` |
| `Synorfo` | `apps/email-signatures/`, the copy before `orfo-web`'s | the signature files |

## Rules

- Everything here is public: only assets meant to be published, never a person's file, an address or a draft.
- A file loaded at `@main` is never renamed or deleted. A new version keeps its name only with the same pixel size, since installed signatures carry their width and height; otherwise it comes under a new name beside the old one. jsDelivr caches a file for about seven days.
- A signature logo is made by `orfo-web`'s `email-signatures/scripts/make-logo.js`, then published here as the same file.

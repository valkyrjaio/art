# AGENTS.md

**valkyrja `art`** — the canonical source for the Valkyrja visual identity. This
repo holds the logos, the banners, and the flow charts. The framework repos, the
ecosystem repos, and the valkyrja.io website all take their images from here.

This is **not** a framework code repo, so only part of the canonical guide
applies.

## Read first

**Cross-language canonical** —
<https://github.com/valkyrjaio/architecture/blob/master/AGENTS.md>

It governs the parts that **do** apply here:

- The `[Root] type:` commit and PR-title format.
- The branch → commit → push → open-PR workflow, with confirmation before each
  write action.
- The current-working-branch policy. This repo uses `26.x`.
- Simplified Technical English in every document.
- Trailing newlines, and American English.

## What does NOT apply

This repo holds no framework code. Ignore the framework-specific sections of the
canonical guide:

- The structure and naming taxonomy — contracts, providers, throwables, and the
  `Abstract\`, `Enum\`, and `Contract\` segments.
- The provider conventions and the binding-key conventions.
- The 100% line-and-branch coverage rule. An image carries no test.
- The license header for a source file.
- The per-language CI gates.

## What this repo holds

- **`full-logo/`** — the primary Valkyrja mark, with the wordmark.
- **`long-banner/`** — the wide banner for a README, a document header, or a
  social card.
- **`thumbnail-logo/`** — the compact mark for an avatar or a favicon.
- **`flow-charts/`** — the technical diagrams. Each language has its own
  directory. The `all/` directory holds the cross-language diagram.
- **The Markdown documents in the root** — `README.md`, `CHANGELOG.md`,
  `LICENSE.md`, and `VERSION.md`.

A brand asset directory groups its files by color, and then by language variant.
`long-banner/orange/php.png` is an example.

## Warning — the license splits this repo in two

`LICENSE.md` gives two groups of files two different sets of terms. Read
`LICENSE.md` before you copy a file out of this repo, and before you add a file
to it.

- **`full-logo/`, `long-banner/`, and `thumbnail-logo/` hold the brand assets.
  All rights are reserved.** The MIT license does not cover these files.
- **`flow-charts/`, `.github/`, and the root Markdown documents are MIT.**

A change that moves a file between these two groups changes the license terms of
that file. State that consequence in the pull request description.

The `README.md` shows every brand asset in a preview table. A new asset, a
renamed asset, and a removed asset each need the matching table row in the same
pull request.

## CI

The gate here checks documents, not code. `ci.yml` runs the trailing newline
check and the Markdown check. `pr.yml` runs the commit message check.

## Roots

Most relevant here: `[Logo]`, `[Banner]`, `[FlowChart]`, `[License]`,
`[Workflow]`, `[GitHub]`, and `[Git]`.

**`[Art]` is not a root in this repo.** A root is never the repo's own identity,
and this repo _is_ the art, so the name says nothing here. Name the asset
instead. `[Art]` stays correct in another repo, where an art file genuinely
stands out.

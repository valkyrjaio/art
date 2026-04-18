<p align="center"><a href="https://valkyrja.io" target="_blank">
    <img src="https://raw.githubusercontent.com/valkyrjaio/art/refs/heads/master/long-banner/orange/default.png" width="100%">
</a></p>

# Valkyrja Art

Art assets for the [Valkyrja][valkyrja url] project — banners, logos, and
flow charts used across the framework, its ecosystem repositories, and the
valkyrja.io website.

This repository is the canonical source for Valkyrja's visual identity. If
you need a logo for a README, a banner for a presentation, or a lifecycle
diagram for documentation, it lives here.

What's Included
---------------

- **Banners** — wide repository banners in language-specific variants
- **Full logos** — the primary Valkyrja mark in language-specific variants
- **Thumbnail logos** — compact marks suitable for avatars and favicons
- **Flow charts** — lifecycle and architecture diagrams per language

Banners
-------

Wide banners suitable for repository READMEs, documentation headers, and
social cards.

### Orange

| Variant | Preview                                    |
|---------|--------------------------------------------|
| Default | ![Default](long-banner/orange/default.png) |
| PHP     | ![PHP](long-banner/orange/php.png)         |
| Java    | ![Java](long-banner/orange/java.png)       |

Full Logos
----------

The primary Valkyrja mark, including wordmark.

### Orange

| Variant | Preview                                  |
|---------|------------------------------------------|
| Default | ![Default](full-logo/orange/default.png) |
| PHP     | ![PHP](full-logo/orange/php.png)         |
| Java    | ![Java](full-logo/orange/java.png)       |

Thumbnail Logos
---------------

Compact marks suitable for avatars, favicons, and other small-format uses.

### Orange

| Variant | Preview                                       |
|---------|-----------------------------------------------|
| Default | ![Default](thumbnail-logo/orange/default.png) |

### Blue

| Variant | Preview                                     |
|---------|---------------------------------------------|
| Default | ![Default](thumbnail-logo/blue/default.png) |
| White   | ![White](thumbnail-logo/blue/white.png)     |

Flow Charts
-----------

Lifecycle and architecture diagrams used in Valkyrja documentation.

### All Languages

Cross-language diagrams that apply to every port.

| Chart               | Preview                                                         |
|---------------------|-----------------------------------------------------------------|
| Exception Hierarchy | ![Exception Hierarchy](flow-charts/all/exception_hierarchy.svg) |

### PHP

| Chart                 | Preview                                                             |
|-----------------------|---------------------------------------------------------------------|
| CLI Lifecycle         | ![CLI Lifecycle](flow-charts/php/cli-lifecycle.svg)                 |
| HTTP Lifecycle        | ![HTTP Lifecycle](flow-charts/php/http-lifecycle.svg)               |
| Worker HTTP Lifecycle | ![Worker HTTP Lifecycle](flow-charts/php/worker-http-lifecycle.svg) |
| Exception Hierarchy   | ![Exception Hierarchy](flow-charts/php/exception-hierarchy.svg)     |

### Java

| Chart               | Preview                                                          |
|---------------------|------------------------------------------------------------------|
| Exception Hierarchy | ![Exception Hierarchy](flow-charts/java/exception_hierarchy.svg) |

### Go

| Chart               | Preview                                                        |
|---------------------|----------------------------------------------------------------|
| Exception Hierarchy | ![Exception Hierarchy](flow-charts/go/exception_hierarchy.svg) |

### Python

| Chart               | Preview                                                            |
|---------------------|--------------------------------------------------------------------|
| Exception Hierarchy | ![Exception Hierarchy](flow-charts/python/exception_hierarchy.svg) |

### TypeScript

| Chart               | Preview                                                                |
|---------------------|------------------------------------------------------------------------|
| Exception Hierarchy | ![Exception Hierarchy](flow-charts/typescript/exception_hierarchy.svg) |

Usage
-----

Link directly to the raw file from GitHub for use in READMEs, documentation,
and external sites:

```
https://raw.githubusercontent.com/valkyrjaio/art/refs/heads/master/{path-to-asset}
```

For example, the default long banner used in ecosystem READMEs:

```
https://raw.githubusercontent.com/valkyrjaio/art/refs/heads/master/long-banner/orange/default.png
```

Contributing
------------

New assets and refinements to existing ones are welcome. See
[`CONTRIBUTING.md`][contributing url] for the submission process,
[`REPOSITORY_NAMING.md`][repository naming url] for how repos are named, and
[`VOCABULARY.md`][vocabulary url] for terminology used across the project.

When adding new assets, follow the existing directory structure:
`{asset-type}/{color-variant}/{language-variant}.{ext}`.

License
-------

Licensed under the [MIT license][MIT license url]. See
[`LICENSE.md`](./LICENSE.md).

[valkyrja url]: https://valkyrja.io

[contributing url]: https://github.com/valkyrjaio/.github/blob/master/CONTRIBUTING.md

[repository naming url]: https://github.com/valkyrjaio/.github/blob/master/REPOSITORY_NAMING.md

[vocabulary url]: https://github.com/valkyrjaio/.github/blob/master/VOCABULARY.md

[MIT license url]: https://opensource.org/licenses/MIT

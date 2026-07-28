# ZeroPress

ZeroPress is a static-first publishing platform for Markdown sites, structured content, reusable themes, WordPress migration, and CMS-grade authoring workflows.

This organization contains the official repositories for the ZeroPress platform, including public sites, Build Pages, the WXR import bridge, theme tooling, runtime validators, Studio, Edge, and contract documentation.

## Start Here

- [zeropress.app](https://zeropress.app/): product overview and public entry point for ZeroPress.
- [build-pages.zeropress.dev](https://build-pages.zeropress.dev/): product documentation for turning a Markdown source directory into a static ZeroPress site.
- [zeropress.page](https://zeropress.page/): bundled theme previews and source examples for Build Pages sites.
- [zeropress.dev](https://zeropress.dev/): technical documentation for preview-data, theme runtime, theme authoring, and CLI contracts.
- [schemas.zeropress.dev](https://schemas.zeropress.dev/): canonical JSON Schema host for ZeroPress contract files.
- [`@zeropress/wxr-import`](https://github.com/zeropress-app/zeropress-wxr-import): WordPress migration CLI for producing canonical Preview Data.

ZeroPress has three public entry points:

- Markdown document publishing with `@zeropress/build-pages`
- WordPress migration from WXR exports with `@zeropress/wxr-import`, followed by `@zeropress/build`
- Direct static builds from `preview-data.json` and a ZeroPress theme with `@zeropress/build`

ZeroPress Studio is being developed as an integrated authoring, import, media-management, and publishing product. It is not publicly released yet.

## Project Status

ZeroPress is currently in beta. The public v0.7 contracts and the build, theme, and WordPress migration toolchain are feature-complete and actively dogfooded across real publishing workflows.

During beta, the focus is compatibility, documentation, external testing, and defect correction. The GitHub Action and public CLI toolchain are available today. Studio and Edge remain unreleased alpha products; they consume the public ZeroPress contracts but do not define the schema contracts or determine their release status.

## Contribution Policy

ZeroPress is currently developed as a maintainer-led project.

At this stage, we are not accepting pull requests for code changes. This helps us keep the architecture consistent and maintain clear code provenance during early development.

Bug reports, feature requests, documentation feedback, and design discussions are welcome through Issues. We appreciate thoughtful feedback and real-world usage reports.

## Core Repositories

- [`zeropress-studio`](https://github.com/zeropress-app/zeropress-studio): Unreleased integrated authoring, import, media-management, and publishing product.
- [`zeropress-edge`](https://github.com/zeropress-app/zeropress-edge): Unreleased optional runtime service for static ZeroPress sites, such as comments and forms.

## Theme Ecosystem

- [`zeropress-theme`](https://github.com/zeropress-app/zeropress-theme): Developer toolkit for building ZeroPress themes.
- [`zeropress-create-theme`](https://github.com/zeropress-app/zeropress-create-theme): Starter generator for scaffolded ZeroPress themes and sample Preview Data.
- [`zeropress-theme-validator`](https://github.com/zeropress-app/zeropress-theme-validator): Runtime validator for ZeroPress themes.

## Build and Validation

- [`zeropress-build`](https://github.com/zeropress-app/zeropress-build): CLI for full ZeroPress builds.
- [`zeropress-build-pages`](https://github.com/zeropress-app/zeropress-build-pages): GitHub Action and CLI for publishing Markdown source directories as static ZeroPress sites.
- [`zeropress-build-core`](https://github.com/zeropress-app/zeropress-build-core): Core library for the ZeroPress build system.
- [`zeropress-preview-data-validator`](https://github.com/zeropress-app/zeropress-preview-data-validator): Runtime contract validator for preview payloads.
- [`zeropress-wxr-import`](https://github.com/zeropress-app/zeropress-wxr-import): CLI for converting WordPress WXR exports into canonical Preview Data.

## Documentation

- [`zeropress.dev`](https://github.com/zeropress-app/zeropress.dev): Technical documentation for ZeroPress contracts, theme authoring, and build tools.
- [`build-pages.zeropress.dev`](https://github.com/zeropress-app/build-pages.zeropress.dev): Product documentation for `@zeropress/build-pages`.
- [`zeropress.page`](https://github.com/zeropress-app/zeropress.page): Theme preview and usage example sites for ZeroPress-maintained themes.
- [`schemas.zeropress.dev`](https://github.com/zeropress-app/schemas.zeropress.dev): Canonical JSON Schema host for ZeroPress contract files.

## Links

- Website: [zeropress.app](https://zeropress.app)
- Build Pages: [build-pages.zeropress.dev](https://build-pages.zeropress.dev)
- Theme previews: [zeropress.page](https://zeropress.page)
- Docs: [zeropress.dev](https://zeropress.dev)
- Schemas: [schemas.zeropress.dev](https://schemas.zeropress.dev)
- License: Open source under Apache-2.0 and MIT.

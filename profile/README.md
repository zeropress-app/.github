# ZeroPress

ZeroPress is a static-first, file-native publishing platform for the modern web.

This organization contains the official repositories for the ZeroPress platform, including backend services, frontend apps, theme tooling, runtime validators, and public documentation.

## Project Status

ZeroPress is currently in alpha and actively dogfooded. The core publishing cycle is working end to end, including preview-data generation, theme rendering, static builds, and hosted deployment workflows.

The v0.6 contracts are being tested against real publishing scenarios. The GitHub Action and CLI toolchain is usable today, while the admin dashboard remains under active development.

## Contribution Policy

ZeroPress is currently developed as a maintainer-led project.

At this stage, we are not accepting pull requests for code changes. This helps us keep the architecture consistent and maintain clear code provenance during early development.

Bug reports, feature requests, documentation feedback, and design discussions are welcome through Issues or Discussions. We appreciate thoughtful feedback and real-world usage reports.

## Core Repositories

- [`zeropress`](https://github.com/zeropress-app/zeropress): Static-first, file-native CMS for the modern web.
- [`zeropress-studio`](https://github.com/zeropress-app/zeropress-studio): Admin UI for managing content and publishing ZeroPress sites.
- [`zeropress-studio-api`](https://github.com/zeropress-app/zeropress-studio-api): Backend API for content operations, media, preview-data generation, and publishing workflows.
- [`zeropress-edge`](https://github.com/zeropress-app/zeropress-edge): Optional public runtime service for static ZeroPress sites, such as comments and forms.

## Theme Ecosystem

- [`zeropress-theme`](https://github.com/zeropress-app/zeropress-theme): Developer toolkit for building ZeroPress themes.
- [`zeropress-create-theme`](https://github.com/zeropress-app/zeropress-create-theme): Starter generator for scaffolded v0.6 themes and sample preview data.
- [`zeropress-theme-validator`](https://github.com/zeropress-app/zeropress-theme-validator): Runtime validator for ZeroPress themes.

## Build and Validation

- [`zeropress-build`](https://github.com/zeropress-app/zeropress-build): CLI for full ZeroPress builds.
- [`zeropress-build-pages`](https://github.com/zeropress-app/zeropress-build-pages): GitHub Action and CLI for building Markdown-based ZeroPress sites.
- [`zeropress-build-core`](https://github.com/zeropress-app/zeropress-build-core): Core library for the ZeroPress build system.
- [`zeropress-preview-data-validator`](https://github.com/zeropress-app/zeropress-preview-data-validator): Runtime contract validator for preview payloads.

## Documentation

- [`zeropress.dev`](https://github.com/zeropress-app/zeropress.dev): Public documentation for ZeroPress contracts, authoring workflows, and build tools.
- [`schemas.zeropress.dev`](https://github.com/zeropress-app/schemas.zeropress.dev): Canonical JSON Schema host for ZeroPress contract files.

## Links

- Website: [zeropress.app](https://zeropress.app)
- Docs: [zeropress.dev](https://zeropress.dev)
- Schemas: [schemas.zeropress.dev](https://schemas.zeropress.dev)
- License: Open source under Apache-2.0 and MIT.

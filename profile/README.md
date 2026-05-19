# ZeroPress

ZeroPress is a static-first, file-native publishing platform for the modern web.

This organization contains the official repositories for the ZeroPress platform, including backend services, frontend apps, theme tooling, runtime validators, and public documentation.

## Project Status

ZeroPress is currently in alpha and actively dogfooded. The core publishing cycle is working end to end, including preview-data generation, theme rendering, static builds, and hosted deployment workflows.

The v0.6 contracts are being tested against real publishing scenarios. The GitHub Action and CLI toolchain is usable today, while the admin dashboard remains under active development.

## Core Repositories

- [`zeropress`](https://github.com/zeropress-app/zeropress): Static-first, file-native CMS for the modern web.
- [`zeropress-core`](https://github.com/zeropress-app/zeropress-core): Backend API for the ZeroPress admin dashboard.
- [`zeropress-studio`](https://github.com/zeropress-app/zeropress-studio): Frontend app for the ZeroPress admin dashboard.
- [`zeropress-pages`](https://github.com/zeropress-app/zeropress-pages): Edge page delivery worker for ZeroPress sites.

## Theme Ecosystem

- [`zeropress-theme`](https://github.com/zeropress-app/zeropress-theme): Developer toolkit for building ZeroPress themes.
- [`zeropress-create-theme`](https://github.com/zeropress-app/zeropress-create-theme): Starter generator.
- [`zeropress-theme-validator`](https://github.com/zeropress-app/zeropress-theme-validator): Runtime validator for ZeroPress themes.

## Build and Validation

- [`zeropress-build`](https://github.com/zeropress-app/zeropress-build): CLI for full ZeroPress builds.
- [`zeropress-build-pages`](https://github.com/zeropress-app/zeropress-build-pages): GitHub Action and CLI for building Markdown-based ZeroPress sites.
- [`zeropress-build-core`](https://github.com/zeropress-app/zeropress-build-core): Core library for the ZeroPress build system.
- [`zeropress-preview-data-validator`](https://github.com/zeropress-app/zeropress-preview-data-validator): Runtime contract validator for preview payloads.

## Documentation

- [`zeropress.dev`](https://github.com/zeropress-app/zeropress.dev): Public runtime documentation and JSON schemas for ZeroPress.

## Links

- Website: [zeropress.app](https://zeropress.app)
- Docs: [zeropress.dev](https://zeropress.dev)
- License: Open source under Apache-2.0 and MIT.

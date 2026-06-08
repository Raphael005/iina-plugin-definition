# iina-plugin-definition

[![npm version](https://img.shields.io/npm/v/iina-plugin-definition.svg)](https://www.npmjs.com/package/iina-plugin-definition)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

TypeScript type definitions for the [IINA](https://iina.io/) plugin API. This package provides complete type safety and IntelliSense support when developing IINA plugins.

## Installation

```sh
yarn add iina-plugin-definition
```

or

```sh
npm i iina-plugin-definition
```

## Setup

Add the package to `typeRoots` in your `tsconfig.json`:

```json
{
  "compilerOptions": {
    "typeRoots": [
      "./node_modules/@types",
      "./node_modules/iina-plugin-definition"
    ]
  }
}
```

## What's Included

This package provides type definitions for the entire IINA plugin API, including:

- **Core API** – Player controls, status, preferences, and event handling
- **HTTP** – Making HTTP requests from plugins
- **Menu** – Creating and managing menu items
- **Tracks** – Video, audio, and subtitle track management
- **Playlist** – Playlist manipulation
- **Chapters** – Chapter navigation
- **Overlay** – Custom overlay views
- **WebViews** – Embedded web views in the player
- **Subtitle Providers** – Custom subtitle source integration
- **Global Entry** – System-wide plugin access

## Documentation

Full documentation is available in the `pages/` directory:

- [Getting Started](pages/getting-started.md)
- [Creating Plugins](pages/creating-plugins.md)
- [Developer Guide](pages/dev-guide.md)
- [WebViews](pages/webviews.md)
- [Subtitle Providers](pages/subtitle-providers.md)
- [Plugin Preferences](pages/plugin-preferences.md)
- [Global Entry](pages/global-entry.md)

## Building Documentation

To generate API documentation locally:

```sh
yarn build
```

This uses [TypeDoc](https://typedoc.org/) to generate HTML documentation from the type definitions.

## Version

Current version: **0.99.3**

## License

[MIT](LICENSE) © IINA Developers

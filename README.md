# Polaris Slideshow

**Version 1.7.0** · Polaris UI plugin · MIT license

A responsive slideshow component with Sass styling and TypeScript/JavaScript behavior.

This repository contains the plugin's source and compiled distribution assets. It is maintained separately from [Polaris Core](https://github.com/sigmascript/polaris-core).

## Install

```bash
npm install polaris-slideshow
```

## Get started

Include the Polaris Core CSS and JavaScript assets, then the slideshow CSS and JavaScript assets in your application. Refer to the source and existing examples for initialization and markup; do not assume the slideshow initializes automatically.

Available production assets in this repository:

- `dist/css/main-rtl.min.css`
- `dist/css/main.min.css`
- `dist/js/main.min.js`

For example, use the appropriate stylesheet from `node_modules/polaris-slideshow/dist/css/` in your application's asset pipeline. A plain HTML project can also copy the required compiled files into its public assets.

## Development

```bash
npm install
npm run css
```

For the complete list of production and watch commands, see [Development](docs/development.md). Development dependencies remain in the plugin repository; they do not need to be deployed with a production website.

## Documentation

- [Documentation index](docs/README.md)
- [Getting started](docs/getting-started.md)
- [Development and build commands](docs/development.md)
- [Changelog](CHANGELOG.md)

## Compatibility

The development toolchain uses Polaris Core 1.0.6 and Sass 1.105.2. Production builds and security audits passed during the maintenance refresh. Slideshow JavaScript runtime regression testing remains a release gate.

## Support and license

Report issues through the [repository issue tracker](https://github.com/sigmascript/polaris-slideshow/issues). Licensed under MIT; see `LICENSE`.

# Getting started

## Install

```bash
npm install polaris-slideshow
```

## Distribution files

- `dist/css/main-rtl.min.css`
- `dist/css/main.min.css`
- `dist/js/main.min.js`

## Integration

Include the Polaris Core CSS and JavaScript assets, then the slideshow CSS and JavaScript assets in your application. Refer to the source and existing examples for initialization and markup; do not assume the slideshow initializes automatically.

When using a package manager, import or copy the appropriate compiled asset from `node_modules/polaris-slideshow/dist/`. Keep source Sass files available when customizing the plugin.

## Important distinctions

- `src/` contains development source.
- `dist/` contains compiled assets intended for consumption.
- `index.js` is not documented here as a browser UI initialization API.
- Existing public CSS names and, where applicable, JavaScript APIs should remain stable during maintenance.

# Static Website Template

This is a template for creating simple static websites without JS frameworks.

Based on this repo:

[https://static-website-template.netlify.com/](https://static-website-template.netlify.com/)

_created by [Vincent Will](https://wweb.dev/)_

It uses:

- SCSS with linting and autoprefixer
- JavaScript with webpack using babel and linting
- minifying images
- html partials and minify with post-html
- browser-sync

The compiled files will go to the directory "/dist"

- from `src/scss` to `dist/index.css`
- from `src/js` to `dist/bundle.js`
- from `src/views` to `dist/`
- from `src/images` to `dist/images`

## Getting Started

1. Install dependencies

```
npm install
```

2. Build resources

```
npm run build
```

3. Watch for changes

```
npm run watch
```

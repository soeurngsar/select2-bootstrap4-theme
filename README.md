# select2-bootstrap4-theme

[Select2](https://github.com/select2/select2) v4 theme for Bootstrap4 (Compatible to boostrap 4.0.0+)

## Live demo

👉 https://ttskch.github.io/select2-bootstrap4-theme/

## Installation

### CDN

```html
<link rel="stylesheet" href="/path/to/select2.css">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@ttskch/select2-bootstrap4-theme@x.x.x/dist/select2-bootstrap4.min.css">
```

### Manually

```bash
# npm
$ npm install @ttskch/select2-bootstrap4-theme

# yarn
$ yarn add @ttskch/select2-bootstrap4-theme

# composer
$ composer require ttskch/select2-bootstrap4-theme
```

```html
<link rel="stylesheet" href="/path/to/select2.css">
<link rel="stylesheet" href="/path/to/select2-bootstrap4.min.css">
```

## Usage

```js
$('select').select2({
    theme: 'bootstrap4',
});
```

## Getting involved

1. Fix [src/_layout.scss](src/_layout.scss), [src/_single.scss](src/_single.scss) or [src/_multiple.scss](src/_multiple.scss)
1. Do `npm run build:both`
1. Send me a Pull Request

You can use [docs](docs) dir for your development.

1. Do `npm run prepare` (this creates symlink to `dist/select2-bootstrap4.css` onto `docs`)
1. Serve `docs` with your local web server (e.g. `php -S localhost:8888 -t docs`)
1. Do `npm run watch`
1. Tweak scss and browse demo page on your browser

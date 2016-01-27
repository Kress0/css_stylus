# css_stylus

A set of utilities using stylus for cross-browser support.

## Installation

To install stylus run:

```bash
$ npm install
```

## Use

Project blank index available in `index.html`. Compatible meta and IE conditional are vital to make things work.

Styles should be written in `css_stylus/style.styl`.

Use conditions to address either IE7 or modern browsers:

```javascript
if ie
    statement
else
    statement
```

## Compilation

In order to start watching for changes and compile them right away run:

```bash
$ npm run compile
```

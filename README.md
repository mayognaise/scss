# SCSS

A reusable SCSS library

## Install

```bash
npm i git+https://github.com/mayognaise/scss.git
```

## Usage

### Default

You can simple call:

```scss
@import 'scss';
```

## Customize variables

If you wish customize variables:

- Create a common scss file to use
- Load initial variable first
- Import customized variable file to overwrite
- Then call all mixin

```scss
// common.scss
@import 'scss/src/variables';
@import 'path/to/your/own/variables';
@import 'scss/src/all-mixin';

// Then call the scss
@import 'path/to/common';
```

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

[Here is the default variables](https://github.com/mayognaise/scss/blob/master/src/variables.scss).

If you wish customize variables:

```scss
// common.scss - Create a common scss file to use
@import 'path/to/your/own/variables'; // Import customized variable file. Don't forget adding
@import 'scss';

// You can use this file as library
@import 'path/to/common';
```

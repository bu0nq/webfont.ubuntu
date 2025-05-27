# WebFont.Ubuntu

Package for integrating `Ubuntu` fonts in a web environment.

![npm](https://img.shields.io/npm/v/@bu0nq/webfont.ubuntu?style=for-the-badge)
![npm](https://img.shields.io/npm/dm/@bu0nq/webfont.ubuntu?style=for-the-badge)
![npm](https://img.shields.io/npm/dt/@bu0nq/webfont.ubuntu?style=for-the-badge)
___

## Installation

This package can be deployed automatically using NPM:

```
npm i @bu0nq/webfont.ubuntu
```

## Usage (CSS)

Font files are located in the `fonts` directory. To import all fonts, you can use:

```css
body {
  font-family: 'Ubuntu', sans-serif;
}
```

### Importing

```css
@import "~@bu0nq/webfont.ubuntu/ubuntu.css";
@import "~@bu0nq/webfont.ubuntu/ubuntu-normal.css";
```

To import specific fonts, you can use:

```css
@import "~@bu0nq/webfont.ubuntu/css/ubuntu-300-normal.css";
@import "~@bu0nq/webfont.ubuntu/css/ubuntu-400-normal.css";
@import "~@bu0nq/webfont.ubuntu/css/ubuntu-500-normal.css";
@import "~@bu0nq/webfont.ubuntu/css/ubuntu-700-normal.css";
```

## Usage (LESS)

Font files are located in the `fonts` directory. To import all fonts, you can use:

```less
body {
  font-family: 'Ubuntu', sans-serif;
}
```

### Importing

```less
@import "~@bu0nq/webfont.ubuntu/ubuntu";
@import "~@bu0nq/webfont.ubuntu/ubuntu-normal";
```

To import specific fonts, you can use:

```less
@import "~@bu0nq/webfont.ubuntu/less/ubuntu-300-normal";
@import "~@bu0nq/webfont.ubuntu/less/ubuntu-400-normal";
@import "~@bu0nq/webfont.ubuntu/less/ubuntu-500-normal";
@import "~@bu0nq/webfont.ubuntu/less/ubuntu-700-normal";
```

## Usage (SCSS)

Font files are located in the `fonts` directory. To import all fonts, you can use:

```scss
body {
  font-family: 'Ubuntu', sans-serif;
}
```

### Importing

```scss
@use "~@bu0nq/webfont.ubuntu/ubuntu";
@use "~@bu0nq/webfont.ubuntu/ubuntu-normal";
```

To import specific fonts, you can use:

```scss
@use "~@bu0nq/webfont.ubuntu/scss/ubuntu-300-normal";
@use "~@bu0nq/webfont.ubuntu/scss/ubuntu-400-normal";
@use "~@bu0nq/webfont.ubuntu/scss/ubuntu-500-normal";
@use "~@bu0nq/webfont.ubuntu/scss/ubuntu-700-normal";
```

## Licensing

It is important to always read the license for every font that you use. Most of the fonts in the collection use the `SIL
Open Font License v1.1`. Some fonts use the `Apache 2.0` license. The Ubuntu fonts use the `Ubuntu Font License v1.0`.

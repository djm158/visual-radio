# \<visual-radio\>

> Visual radio  ** Not use in production  **

[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg?style=flat-square?style=flat-square)](https://www.webcomponents.org/element/miguelsmuller/visual-radio)

## Install ##

Install the component using [Bower](http://bower.io/):

```sh
$ bower install visual-radio --save
```

## Usage ##

1. Import Web Components' polyfill, if needed:

```html
<script src="bower_components/webcomponentsjs/webcomponents.min.js"></script>
```

2. Import Custom Element:

```html
<link rel="import" href="/bower_components/visual-radio/visual-radio.html"> 
```

3. Start using it!

```html
<visual-radio radio-value="bob" radio-image="http://i.pravatar.cc/300" radio-text="Bob Milton"></visual-radio>
<visual-radio radio-value="mark" radio-image="http://i.pravatar.cc/300" radio-text="Mark Muller" selected></visual-radio>
<visual-radio radio-value="patrick" radio-text="Patrick Luis"></visual-radio>
<visual-radio radio-value="josep" radio-text="Li Topher" selected></visual-radio>
```

## [Contributing and Development](CONTRIBUTING.md)
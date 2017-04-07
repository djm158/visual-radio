# \<visual-radio\>

[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg?style=flat-square?style=flat-square)](https://www.webcomponents.org/element/miguelsmuller/visual-radio) [![](https://img.shields.io/github/issues-raw/badges/shields.svg)](https://github.com/miguelsmuller/visual-radio) [![Bower](https://img.shields.io/bower/v/bootstrap.svg)](https://github.com/miguelsmuller/visual-radio)

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
<visual-radio value="bob" label="Bob Milton" image="http://i.pravatar.cc/300"></visual-radio>
<visual-radio value="mark" label="Mark Muller" image="http://i.pravatar.cc/300" selected></visual-radio>
<visual-radio value="patrick" label="Patrick Luis"></visual-radio>
<visual-radio value="josep" label="Li Topher" selected></visual-radio>
```

## API reference ##

Custom property                                 | Description                                 | Default
------------------------------------------------|---------------------------------------------|--------------
`--hover-color`                                 | Main color of selected item                 | `#1CAFF6`
`--hover-color-contrast`                        | Opposite color of selected item             | `#FFFFFF`

```css
<style type="text/css">
  visual-radio {
    --hover-color: #ff0000;
    --hover-color-contrast: #000000;
  }
</style>
```

## [Contributing and Development](CONTRIBUTING.md)
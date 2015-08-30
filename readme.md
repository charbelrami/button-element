# Button Element

## Contents

- [Introduction](#introduction)
- [Installation](#installation)
  - [Bower](#bower)
  - [npm](#npm)
- [Usage](#usage)
  - [index.html](#indexhtml)
  - [Running locally](#running-locally)
- [Reference](#reference)
  - [CSS Custom Properties](#css-custom-properties)
  - [Attributes](#attributes)
- [Browser support](#browser-support)
- [Contributing](#contributing)
- [Related](#related)
- [License](#license)

## Introduction

Button element using Polymer and Flexbox

## Installation

### Bower

```
$ bower install button-element
```

### npm

```
$ npm install button-element
```

## Usage

### index.html

```html
<!doctype html>
<html>
  <head>
    <script src="bower_components/webcomponentsjs/webcomponents-lite.min.js"></script>
    <link rel="import" href="bower_components/button-element/button-element.html">
  </head>
  <body>
    <button-element>
      <a href="">
        <paper-ripple></paper-ripple>
        Home
      </a>
    </button-element>
  </body>
</html>
```

### Running locally

#### polyserve

```
$ npm install --global polyserve
```

```
$ polyserve
```

## Reference

### CSS Custom Properties

```css
--button-width
--button-min-height
--button-padding-vertical
--button-padding-horizontal
--button-background-color
--button-background-color-hover
--button-text-color
--button-font-family
--button-font-size
--button-font-weight
--button-border-radius
--button-border-width
--button-border-style
--button-border-color
```

### Attributes

- `border`

```html
<button-element border></button-element>
```

- `start`

```html
<button-element start></button-element>
```

- `end`

```html
<button-element end></button-element>
```

## Browser support

- [webcomponents.js](https://github.com/webcomponents/webcomponentsjs#browser-support)
- [Flexbox](http://caniuse.com/#feat=flexbox)

## Contributing

[Contributing](contributing.md)

## Related

- [Grid Element](https://github.com/charbelrami/grid-element)
- [Flex Element](https://github.com/charbelrami/flex-element)

## License

© 2015 Charbel Rami

[MIT](license.txt)

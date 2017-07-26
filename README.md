# cssgrid

Responsive CSS helper classes based on [CSS3 Grid Layout module](https://www.w3.org/TR/css-grid-1/).

View [demo](https://bordertech.github.io/cssgrid/demo).

## Building

Use [yarn](https://yarnpkg.com/) to build.

1. `yarn install` (first time only)
2. `yarn build`

## IE support

IE is kinda broke. We have some beginnings of support but it does not yet include any attempt to set the `-ms-grid-column` offsets or use margins instead of `grid-space`. The file `ie.scss` will be built as a separate file. There is a var which allows this same IE specific CSS to be built into the main CSS file if required.

## Tests

The tests are not really set up yet. The `/test/` directory contains a couple of primitive HTML pages which depend on the built CSS. This is still very much a work in progress.

## Configuration

Configuration is done through Sass variables. More info later!

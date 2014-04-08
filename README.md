# &lt;b-tooltip&gt;

A [Bosonic](http://bosonic.github.io) tooltip element which uses [Tether](http://github.hubspot.com/tether/), an excellent library with no dependencies by [HubSpot](https://github.com/HubSpot).

[Check the demo](http://bosonic.github.io/demos.html).

## Install

This element is available as a npm package, see the [Bosonic documentation](http://bosonic.github.io/documentation.html) for Bosonic transpiler usage.

```sh
$ npm install --save b-tooltip
```

Otherwise, you can download and include in your HTML file the builded CSS & JS files, alongside with Bosonic polyfills, as described in the [Getting Started](http://bosonic.github.io/getting-started.html) guide.

## Usage

```html
<input id="my-input" type="text" value="" placeholder="Value...">
...
<b-tooltip target="#my-input" position="bottom center">
    <p>This is an exciting input field!</p>
</b-tooltip>
```

## API

### Attributes
- __target__: a CSS selector that points to the element the tooltip must be attached to.
- __position__: where the tooltip must be attached (possible values: 'top left', 'left top', 'left middle', 'left bottom', 'bottom left', 'bottom center', 'bottom right', 'right bottom', 'right middle', 'right top', 'top right', 'top center'.

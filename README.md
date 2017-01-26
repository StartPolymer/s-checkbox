[![Published on webcomponents.org][webcomponents-image]][webcomponents-url]

# \<s-paper-checkbox\>

`s-paper-checkbox` is a [material design checkbox](https://material.io/guidelines/components/selection-controls.html#selection-controls-checkbox).
User can tap the checkbox to check or uncheck it. Usually you use checkboxes
to allow user to select multiple options from a set. If you have a single
ON/OFF option, avoid using a single checkbox and use `paper-toggle-button`
instead.

`s-paper-checkbox` is up-to-date fork of [`paper-checkbox`](https://github.com/PolymerElements/paper-checkbox).

## New Features

- [Fix colors by Material Design](https://github.com/StartPolymer/s-paper-checkbox/commit/6e5241b43786071277cc7a13eee7a5c91f1a238d)
- [Support for custom prefix element](https://github.com/StartPolymer/s-paper-checkbox/commit/710c8b946738c9b9042e43b6844e940d6e8e0429), which is displayed before the checkbox itself. From `paper-input` element.

## Demo

[Full demo][webcomponents-demo]

## Usage

<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="paper-checkbox.html">
    <style is="custom-style">
      paper-checkbox {
        font-family: 'Roboto', sans-serif;
        margin: 24px;
      }

      paper-checkbox:first-child {
        --primary-color: #ff5722;
      }

      paper-checkbox.styled {
        align-self: center;
        border: 1px solid var(--paper-green-200);
        padding: 8px 16px;
        --paper-checkbox-checked-color: var(--paper-green-500);
        --paper-checkbox-checked-ink-color: var(--paper-green-500);
        --paper-checkbox-unchecked-color: var(--paper-green-900);
        --paper-checkbox-unchecked-ink-color: var(--paper-green-900);
        --paper-checkbox-label-color: var(--paper-green-500);
        --paper-checkbox-label-spacing: 0;
        --paper-checkbox-margin: 8px 16px 8px 0;
        --paper-checkbox-vertical-align: top;
      }

      paper-checkbox .subtitle {
        display: block;
        font-size: 0.8em;
        margin-top: 2px;
        max-width: 150px;
      }
    </style>
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<paper-checkbox checked>Checked</paper-checkbox>
<paper-checkbox class="styled">
  <div prefix>&bull;&nbsp;</div>
  Checkbox
  <span class="subtitle">
    With a longer label
  </span>
</paper-checkbox>
<paper-checkbox disabled>Disabled</paper-checkbox>
```

## Installation

`bower i s-paper-checkbox -S`

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your application locally.

## Viewing Your Application

```
$ polymer serve
```

## Building Your Application

```
$ polymer build
```

This will create a `build/` folder with `bundled/` and `unbundled/` sub-folders
containing a bundled (Vulcanized) and unbundled builds, both run through HTML,
CSS, and JS optimizers.

You can serve the built versions by giving `polymer serve` a folder to serve
from:

```
$ polymer serve build/bundled
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.

## License

MIT: [StartPolymer/license](https://github.com/StartPolymer/license)

[webcomponents-image]: https://img.shields.io/badge/webcomponents.org-published-blue.svg
[webcomponents-url]: https://beta.webcomponents.org/element/StartPolymer/s-paper-checkbox
[webcomponents-demo]: https://beta.webcomponents.org/element/StartPolymer/s-paper-checkbox/demo/demo/index.html

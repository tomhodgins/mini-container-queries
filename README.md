# mini-container-queries
The World's Smallest Container Query Plugin

## Usage

Define a 'container' using a CSS selector, run a JavaScript test on matching HTML elements, and apply CSS styles to the container or its child elements if the test resolves `true`.

## Syntax

```javascript
q(containerList, condition, childList, rule)
```

- `containerList` is a comma-separated string containing one or more CSS selectors
- `condition` is a JavaScript test that should evaluate to `true` or `false`
- `childList` is a comma-separated string containing one or more CSS selectors
- `rule` is a semicolon-separated string containing one or more CSS declarations

## Example

```javascript
q('div', 'this.offsetWidth > 500', 'span', 'background: lime')
```

## Demo

- [View mini-container-query demo](https://tomhodgins.github.io/mini-container-queries/test/)

## Golfers

This plugin lovingly golfed by:

- [@innovati](https://twitter.com/innovati)
- [@xen](https://twitter.com/Xen_the)
- …you?
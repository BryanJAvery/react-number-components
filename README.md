# react-number-format

React Number Format is an input-formatter library with a sophisticated and light weight caret engine. It ensures that a user can only enter text that meets specific numeric or string patterns, and formats the input value for display.

### Features

1. Prefix, suffix and thousands separator.
1. Input Masking.
1. Format number in an input or format as a simple text.
1. Custom pattern formatting.
1. Custom formatting handler.
1. Fully customizable

### Demos

See the many DEMO sections in [the documentation](documentation/v5/docs/props.md).

### Install

[![npm](https://img.shields.io/npm/dm/react-number-format.svg)](https://www.npmjs.com/package/react-number-format)

Using `npm`

```
npm install react-number-format
```

Using `yarn`

```
yarn add react-number-format
```

### Documentation

Read the [full documentation](documentation/v5/docs/intro.md).

#### ES6

Numeric Format

```js
import { NumericFormat } from 'react-number-format';
```

NumericFormat Props: [documentation/v5/docs/numeric_format.md](documentation/v5/docs/numeric_format.md)

Pattern Format

```js
import { PatternFormat } from 'react-number-format';
```

PatternFormat Props: [documentation/v5/docs/pattern_format.md](documentation/v5/docs/pattern_format.md)

### Migrate from v4 to v5

[Migration guide](documentation/v5/docs/migration.md)

### v4 doc

[v4 Docs](documentation/v4.md)

### Development

- Clone the repository or download the zip
- `npm i -g yarn` to download Yarn
- `yarn` to install dependencies
- `yarn start` to run example server (<http://localhost:8084/>)
- `yarn test` to test changes
- `yarn build` to bundle files

#### Testing

Test cases are written in jasmine and run by karma

Test files : /test/\*\*/\*.spec.js

To run test : `yarn test`

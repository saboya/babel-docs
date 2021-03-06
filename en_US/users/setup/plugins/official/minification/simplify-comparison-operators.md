# Simplify Comparison Operators

Convert `===` and `!==` to `==` and `!=` if their types are inferred to be the
same.

## Example

**Input**

```js
typeof value === "object";
```

**Output**

```js
typeof value == "object";
```

> Note that the output may not be exactly what is above. Babel's implementation
> may have changed since this document was last updated, or the output may have
> been cleaned up for clarity.

## Setup

### Installation

```sh
$ npm install --save-dev babel-plugin-transform-simplify-comparison-operators
```

### Usage

#### Via `.babelrc` (recommended)

**`.babelrc`**

```json
{
  "plugins": ["transform-simplify-comparison-operators"]
}
```

#### Via CLI

```sh
babel script.js --plugin transform-simplify-comparison-operators
```

#### Via Node API

```js
require("babel-core").transform("code", {
  plugins: ["transform-simplify-comparison-operators"]
});
```

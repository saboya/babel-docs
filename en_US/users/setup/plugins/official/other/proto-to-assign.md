# Proto to Assign

## Example

**Input**

```js
```

**Output**

```js
```

> Note that the output may not be exactly what is above. Babel's implementation
> may have changed since this document was last updated, or the output may have
> been cleaned up for clarity.

## Setup

### Installation

```sh
$ npm install --save-dev babel-plugin-transform-proto-to-assign
```

### Usage

#### Via `.babelrc` (recommended)

**`.babelrc`**

```json
{
  "plugins": ["transform-proto-to-assign"]
}
```

#### Via CLI

```sh
babel script.js --plugin transform-proto-to-assign
```

#### Via Node API

```js
require("babel-core").transform("code", {
  plugins: ["transform-proto-to-assign"]
});
```

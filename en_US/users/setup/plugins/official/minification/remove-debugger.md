# Remove Debugger

Remove `debugger` statements

## Example

**Input**

```js
debugger;
method();
```

**Output**

```js
method();
```

> Note that the output may not be exactly what is above. Babel's implementation
> may have changed since this document was last updated, or the output may have
> been cleaned up for clarity.

## Setup

### Installation

```sh
$ npm install --save-dev babel-plugin-transform-remove-debugger
```

### Usage

#### Via `.babelrc` (recommended)

**`.babelrc`**

```json
{
  "plugins": ["transform-remove-debugger"]
}
```

#### Via CLI

```sh
babel script.js --plugin transform-remove-debugger
```

#### Via Node API

```js
require("babel-core").transform("code", {
  plugins: ["transform-remove-debugger"]
});
```

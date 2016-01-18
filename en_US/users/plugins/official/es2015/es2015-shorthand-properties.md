### Installation

```sh
$ npm install --save-dev babel-plugin-es2015-shorthand-properties
```

### Usage

#### Via `.babelrc` (recommended)

**`.babelrc`**

```json
{
  "plugins": ["es2015-shorthand-properties"]
}
```

#### Via CLI

```sh
babel script.js --plugin es2015-shorthand-properties
```

#### Via Node API

```js
require("babel-core").transform("code", {
  plugins: ["es2015-shorthand-properties"]
});
```
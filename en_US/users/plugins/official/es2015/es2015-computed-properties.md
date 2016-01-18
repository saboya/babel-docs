### Installation

```sh
$ npm install --save-dev babel-plugin-es2015-computed-properties
```

### Usage

#### Via `.babelrc` (recommended)

**`.babelrc`**

```json
{
  "plugins": ["es2015-computed-properties"]
}
```

#### Via CLI

```sh
babel script.js --plugin es2015-computed-properties
```

#### Via Node API

```js
require("babel-core").transform("code", {
  plugins: ["es2015-computed-properties"]
});
```
# @babel/plugin-syntax-export-namespace

> Allow parsing of `export namespace from`.

## Installation

```sh
npm install --save-dev @babel/plugin-syntax-export-namespace
```

## Usage

### Via `.babelrc` (Recommended)

**.babelrc**

```json
{
  "plugins": ["@babel/plugin-syntax-export-namespace"]
}
```

### Via CLI

```sh
babel --plugins @babel/plugin-syntax-export-namespace script.js
```

### Via Node API

```javascript
require("@babel/core").transform("code", {
  plugins: ["@babel/plugin-syntax-export-namespace"]
});
```

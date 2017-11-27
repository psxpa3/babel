# @babel/plugin-syntax-export-default

> Allow parsing of export default from.

## Installation

```sh
npm install --save-dev @babel/plugin-syntax-export-default
```

## Usage

### Via `.babelrc` (Recommended)

**.babelrc**

```json
{
  "plugins": ["@babel/plugin-syntax-export-default"]
}
```

### Via CLI

```sh
babel --plugins @babel/plugin-syntax-export-default script.js
```

### Via Node API

```javascript
require("@babel/core").transform("code", {
  plugins: ["@babel/plugin-syntax-export-default"]
});
```

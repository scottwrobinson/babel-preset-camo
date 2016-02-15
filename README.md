# babel-preset-camo

> Babel preset for all es2015 plugins supported by Camo

## Install

```sh
$ npm install --save-dev babel-preset-camo
```

## Usage

### Via `.babelrc` (Recommended)

**.babelrc**

```json
{
  "presets": ["camo"]
}
```

### Via CLI

```sh
$ babel script.js --presets camo 
```

### Via Node API

```javascript
require("babel-core").transform("code", {
  presets: ["camo"]
});
```

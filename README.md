# eslint-plugin-patternfly-console-plugin

This package provides PatternFly linting specifically around they console plugins. These linting rules focus on console plugin development for openshift.

### Installing

```
yarn add -D eslint-plugin-patternfly-console-plugin
```

or

```
npm install eslint-plugin-patternfly-console-plugin --save-dev
```

### Usage

Add eslint-plugin-patternfly-console-plugin to your `.eslintrc.json` or `.eslintrc.js`.

.eslintrc.json:

```json
{
  "plugins": ["plugin:patternfly-console-plugin/recommended"]
}
```

.eslintrc.js:

```js
module.exports = {
  root: true,
  extends: ['plugin:patternfly-console-plugin/recommended']
};
```

### Building

```
yarn build
```

Note the build scripts for this are located in the root package.json under `yarn build`.

### Publishing

```
yarn publish
```

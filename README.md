# eslint-config-okta

Shared [ESLint](https://eslint.org/) config for Okta products.

In addition to generic JS linter rules, this includes rules for TypeScript, React, and Node.js.


## Usage

There are two configurations available for use, either `eslint-config-okta`, or `eslint-config-okta/strict`. The base configuration helps with transitioning over to the strict configuration.

In your project's `package.json`:

```
  "eslintConfig": {
    "extends": "eslint-config-okta/strict"
  },
```

...or in your project's `.eslintrc`:

```
"extends": [
  "eslint-config-okta/strict"
],
```

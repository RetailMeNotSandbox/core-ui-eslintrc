# @retailmenot/core-ui-eslintrc

ESLint rules for RetailMeNot Core UI projects.

# Installation

```
npm install @retailmenot/core-ui-eslintrc
```

# Usage

## ES5

Include this module as a dependency in your package.json, then add an `extends`
rule to your `.eslintrc`. You may also add rules to your `.eslintrc` to override
the defaults pulled in from this project.

```
{
  extends: "./node_modules/@retailmenot/core-ui-eslintrc/.eslintrc"
}
```

## ES6

Same as ES5, but specify the ES6 ruleset in the `extends` rule:

```
{
    extends: "./node_modules/@retailmenot/core-ui-eslintrc/.eslintrc-es6"
}
```

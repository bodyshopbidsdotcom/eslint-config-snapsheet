# eslint-config-snapsheet

Snapsheet shared ESLint configuration

## Usage
Install dependencies

```shell
npm install eslint babel-eslint eslint-plugin-react eslint-config-snapsheet --save-dev
```

Create a `.eslintrc` file with the following:

```yaml
extends:
  - eslint-config-snapsheet
```


## Making Changes
run `npm link` in this directory

In a repository that uses this, run `npm link eslint-config-snapsheet` and you should be able to see your changes directly by triggering the linter. Then commit, bump the version, add changes in CHANGELOG.md, and publish.

You may also override specific rules in consuming repositories without affecting all repositories.

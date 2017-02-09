# eslint-config-snapsheet

ESLint configuration

## Usage
Install dependencies

```shell
yarn add eslint babel-eslint eslint-plugin-react eslint-config-snapsheet -D
```

Create a `.eslintrc` file with the following:

```yaml
extends:
  - eslint-config-snapsheet
```


## Making Changes
run `yarn link` in this directory

In a repository that uses this, run `yarn link eslint-config-snapsheet` and you should be able to see your changes directly by triggering the linter. Then commit, bump the version, add changes in CHANGELOG.md, and publish.

You may also override specific rules in consuming repositories without affecting all repositories.

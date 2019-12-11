# cheatsheet
Cheatsheet for writing codemods and tools

## Tools
- [codemod-cli](https://github.com/rwjblue/codemod-cli)
- [jscodeshift](https://github.com/facebook/jscodeshift)
- [ember-template-recast](https://github.com/ember-template-lint/ember-template-recast)
- [ember-cli-update](https://github.com/ember-cli/ember-cli-update)
- [ember-cli-update-codemods-manifest](https://github.com/ember-cli/ember-cli-update-codemods-manifest)
- [recast](https://github.com/benjamn/recast)
- [ast-builder](https://rajasegar.github.io/ast-builder/)
- [ast-finder](https://rajasegar.github.io/ast-finder/)

## ember-cli-update

### Running codemods
You can run codemods during your app/addon upgrades with [ember-cli-update](https://github.com/ember-cli/ember-cli-update) using the following command:

```sh
ember-cli-update --run-codemods
```

### List available codemods

```sh
ember-cli-update --list-codemods
```
## Awesome Lists
- [awesome-ast](https://github.com/cowchimp/awesome-ast)
- [awesome-jscodeshift](https://github.com/sejoker/awesome-jscodeshift)

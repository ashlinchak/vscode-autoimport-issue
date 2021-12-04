# VSCode auto import with monorepo

Bootstrap packages:

```shell
yarn
npx lerna bootstrap
npx lerna exec -- tsc
```

VSCode's auto importing is working only if package has entry point:

![](assets/images/no-auto-import-suggestion.png)

# ts-node-boilerplate

Boilerplate code for my own applications using [TypeScript][typescript] and [Nodejs][nodejs].
Based on [node-typescript-boilerplate][nodetsboilerplate].

## Dependencies
- [ESLint][eslint]: Basic linting. Opted for Airbnb rule-set.
- [Prettier][prettier]: Responsible for code styling. Installed as an ESLint plugin. 
- [Jest][jest]: Testing framework of choice. Comes with an example test.
- [ts-node-dev][tsnodedev]: Fast file change tracker. I prefer it to nodemon/node-dev.
- [tsconfig-paths][tsconfigpaths]: Works with ts-node-dev to allow module aliasing. Comes with an example module.
- [tsc-alias][tscalias]: Does path replacement in transpiled files.
- [husky][huskyurl]: Git lifecycle hooks.
- [lint-staged][lintstaged]: Coupled with husky, it is responsible for linting staged files only.
- [rimraf][rimrafurl]: For cleaning up build files.
- [dotenv][dotenvurl]: Environment variables.

[nodejs]: https://nodejs.org/dist/latest-v14.x/docs/api/
[typescript]: https://www.typescriptlang.org/
[nodetsboilerplate]: https://github.com/jsynowiec/node-typescript-boilerplate
[jest]: https://facebook.github.io/jest/
[eslint]: https://github.com/eslint/eslint
[prettier]: https://prettier.io
[tsnodedev]: https://github.com/wclr/ts-node-dev
[huskyurl]: https://github.com/typicode/husky
[lintstaged]: https://github.com/okonet/lint-staged
[tsconfigpaths]: https://github.com/dividab/tsconfig-paths
[rimrafurl]: https://github.com/isaacs/rimraf
[dotenvurl]: https://github.com/motdotla/dotenv
[tscalias]: https://github.com/justkey007/tsc-alias
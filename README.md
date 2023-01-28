# @sensible-ts/semantic-release

[![npm version](https://img.shields.io/npm/v/@sensible-ts/semantic-release/latest)](https://www.npmjs.com/package/@sensible-ts/semantic-release)
[![semantic-release: conventional commits](https://img.shields.io/badge/semantic_release-conventional_commits-e10079?logo=semantic-release)](https://github.com/semantic-release/semantic-release)
[![license: MIT](https://img.shields.io/npm/l/@sensible-ts/semantic-release)](LICENSE)

A sensible [semantic-release] config. The main purpose of this configuration is twofold: use `main` as the tracking branch and use the [Conventional Commits] standard instead of the Angular standard. All other defaults are left untouched.

## Usage

First, install this package as a dev dependency.

```shell
npm install --save-dev @sensible-ts/semantic-release
```

Then, add the following to your `package.json`.

```json
{
  "release": {
    "extends": "@sensible-ts/semantic-release"
  }
}
```

## License

Licensed under the [MIT License](LICENSE).

[semantic-release]: https://github.com/semantic-release/semantic-release
[conventional commits]: https://www.conventionalcommits.org/en/v1.0.0/

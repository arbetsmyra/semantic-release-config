# [`semantic-release-config`](https://github.com/arbetsmyra/semantic-release-config)

Arbetsmyra's [semantic-release config](https://github.com/semantic-release/semantic-release/blob/master/docs/usage/configuration.md#configuration)

[![latest git version](https://img.shields.io/github/v/tag/arbetsmyra/semantic-release-config?label=version)](https://github.com/arbetsmyra/semantic-release-config)
[![latest npm version](https://img.shields.io/npm/v/@arbetsmyra/semantic-release-config)](https://www.npmjs.com/package/@arbetsmyra/semantic-release-config)
[![license](https://img.shields.io/github/license/arbetsmyra/semantic-release-config)](https://github.com/arbetsmyra/semantic-release-config/blob/master/LICENSE)

## Installation

### Requirements

- `node` >= v10
- `npm` >= v5

```bash
npm install --save-dev @arbetsmyra/semantic-release-config
```

## Usage

Once the `@arbetsmyra/semantic-release-config` package is installed, you can use it by specifying the `@arbetsmyra/semantic-release-config` config for the [`extends`](https://github.com/semantic-release/semantic-release/blob/master/docs/usage/configuration.md#extends) property in the [semantic-release configuration](https://github.com/semantic-release/semantic-release/blob/master/docs/usage/configuration.md#configuration-file).

`.releaserc`:

```json
{
  "extends": ["@arbetsmyra/semantic-release-config"]
}
```

`package.json`:

```json
{
  "release": {
    "extends": ["@arbetsmyra/semantic-release-config"]
  }
}
```

For scoped packages it is recommended to use the following publish config:

`package.json`:

```json
{
  "publishConfig": {
    "access": "public"
  }
}
```

## Contributing

If you want to contribute and make our project better, your help is very welcome.

## License

[MIT © Arbetsmyra](https://choosealicense.com/licenses/mit/)

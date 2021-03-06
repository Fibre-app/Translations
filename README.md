# Translations

[![Azure DevOps builds (branch)](https://img.shields.io/azure-devops/build/fibre-app/1a84d4c7-ebcc-4ca3-8338-ccd5c297ca2f/20/master?label=Build)](https://dev.azure.com/Fibre-App/Fibre/_build)
[![Azure DevOps tests (branch)](https://img.shields.io/azure-devops/tests/fibre-app/1a84d4c7-ebcc-4ca3-8338-ccd5c297ca2f/20/master?label=Tests)](https://dev.azure.com/Fibre-App/Fibre/_build)
[![npm (scoped)](https://img.shields.io/npm/v/@fibre/translations?color=brightgreen&label=NPM&logo=npm)](https://www.npmjs.com/package/@fibre/types)

## Usage

Feel free to add or edit translations in existing files.

If you wish, you can add new files for different languages or dialects. File names should be [language tags](https://en.wikipedia.org/wiki/Language_localisation#Language_tags_and_codes). They do not need to be official values, but they should make sense.

Language files do not need to be complete, but all should extend at least one other file - [en-gb.json](./translations/en-gb.json) is the base.

Updates to this repository will be integrated into Fibre in the very next update: major, minor, or patch.

## Tests

```
$ npm install

$ npm run test
```

## Licence

Please see [LICENSE.md](./LICENSE.md)

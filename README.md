# NextJS starter-kit

## Description

Bare-bone repo based on nextJS.

## Configuration

1. Search `PROJECT__NAME` word to change.
2. add favicon by [realfavicongenerator](https://realfavicongenerator.net/) and place it into [public](./public/).
3. Modify metadata and chromatic token in [package.json](./package.json).

## Demo

[demo]()

## Contribution

### Installation

```bash
git clone https://github.com/**/*.git
cd **
npm i
```

### Managing

In [package.json](./package.json) you can find useful scripts for managing the project. To run script, use the following command:

```bash
npm run {script-name}
```

Script-names:

- dev - just builds bundles and place it into .next directory;
- build - build minify bundles and place it into .next directory;
- start - builds bundles and runs server to be upgraded;
- test - runs tests;
- lint - lint styles and scripts, show result;
- lint:fix - use prettier for all known files, lint styles and scripts, auto fix files with errors if it is possible, show result;
- storybook - runs storybook.

# WeasyPrint + Pug + Sass template

**A template to get started quickly with WeasyPrint + Pug + Sass.**

## Requirements

- [Node.js](https://nodejs.org/)
- [Yarn](https://yarnpkg.com/)
- [Python](https://www.python.org/)

## Usage

1. Clone this repository or [download a ZIP archive](https://github.com/Calinou/weasyprint-pug-sass-template/archive/master.zip).

2. Install the project dependencies:

```bash
# Make sure `weasyprint` is available in the PATH after installation
pip install --user weasyprint
yarn install
```

Only Yarn is currently supported. npm may be supported in the future,
but keep in mind running scripts using Yarn is slightly faster than npm.

3. Run one of the commands below to start development
   or build for production. The source files are located in `src/`;
   if all goes well, the generated PDF will be available in `dist/`.

## Available npm scripts

```bash
# Watch for changes and rebuild automatically
yarn dev

# Build once for production
yarn prod

# Remove generated files
yarn clean
```

## License

Copyright © 2018 Hugo Locurcio and contributors

Unless otherwise specified, files in this repository are licensed under
the MIT license; see [LICENSE.md](LICENSE.md) for more information.

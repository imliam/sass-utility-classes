# Sass Utility Classes

[![License](https://img.shields.io/github/license/imliam/sass-utility-classes.svg)](LICENSE.md)

This package contains exclusively utility classes. These classes are not opinionated or styled in any way, and can be used for rapidly designing unique components.

<!-- TOC -->

- [Sass Utility Classes](#sass-utility-classes)
    - [💾 Installation](#💾-installation)
    - [📝 Usage](#📝-usage)
    - [🛠 Development](#🛠-development)
    - [💄 Tailwind CSS](#💄-tailwind-css)
    - [🔖 Changelog](#🔖-changelog)
    - [⬆️ Upgrading](#⬆️-upgrading)
    - [🎉 Contributing](#🎉-contributing)
    - [👷 Credits](#👷-credits)
    - [♻️ License](#♻️-license)

<!-- /TOC -->

## 💾 Installation

You can install the package with [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/) using the following commands:

```bash
# With NPM
npm install sass-utility-classes --save-dev

# With Yarn
yarn add sass-utility-classes --dev
```

## 📝 Usage

If using Sass in your own project, you can import the utility classes using the following directive:

```scss
@import "~sass-utility-classes/src/styles";
```

You can instead include the prebuilt `styles.css` file from the build directory as a regular CSS file in your HTML.

```html
<link rel="stylesheet" href="/link/to/built/styles.css" />
```

The utility classes names can be found in the source files.

## 🛠 Development

Sass Utility Classes includes [Laravel Mix](https://github.com/JeffreyWay/laravel-mix) as a build tool that wraps around Webpack. If you wish to recompile the source Sass files to CSS, you can run one of the following commands:

```bash
# Compile the files
npm run dev

# Watch the source files and automatically recompile when a change is made
npm run watch

# Compile the files for production, minifying the output
npm run production
```

## 💄 Tailwind CSS

Most of the utilities found in this package are named and styled based off of the [TailwindCSS](https://tailwindcss.com/) utility library project.

You can find examples and additional explanation for each of the utilities from the TailwindCSS documentation.

**Note that this is not a direct port of TailwindCSS. There are a handful of additional utility classes, some from TailwindCSS are not included, and the configuration methods are completely different.**

## 🔖 Changelog

Please see [the changelog file](CHANGELOG.md) for more information on what has changed recently.

## ⬆️ Upgrading

Please see the [upgrading file](UPGRADING.md) for details on upgrading from previous versions.

## 🎉 Contributing

Please see the [contributing file](CONTRIBUTING.md) and [code of conduct](CODE_OF_CONDUCT.md) for details on contributing to the project.

## 👷 Credits

- [Liam Hammett](https://github.com/imliam)
- [All Contributors](../../contributors)

## ♻️ License

The MIT License (MIT). Please see the [license file](LICENSE.md) for more information.

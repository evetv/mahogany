<p align="center">
  <img width="300px" src="./docs/src/readme.png">
</p>

<h1 align="center">Mahogany</h1>

<p align="center"><a href="https://github.com/evetv/eve" target="_blank">Eve</a>'s Custom Fork of GitHub's Primer CSS Framework</p>

<p align="center">
  <a aria-label="npm package" href="https://www.npmjs.com/package/@evetv/css">
    <img alt="" src="https://img.shields.io/npm/v/@evetv/css.svg">
  </a>
  <a aria-label="build status" href="https://github.com/evetv/mahogany/actions/workflows/ci.yml">
    <img alt="" src="https://github.com/evetv/mahogany/actions/workflows/ci.yml/badge.svg">
  </a>
  <a aria-label="contributors graph" href="https://github.com/evetv/mahogany/graphs/contributors">
    <img src="https://img.shields.io/github/contributors/evetv/mahogany.svg">
  </a>
  <a aria-label="last commit" href="https://github.com/evetv/mahogany/commits/main">
    <img alt="" src="https://img.shields.io/github/last-commit/evetv/mahogany.svg">
  </a>
  <a aria-label="license" href="https://github.com/evetv/mahogany/blob/main/LICENSE">
    <img src="https://img.shields.io/github/license/evetv/mahogany.svg" alt="">
  </a>
</p>

## Documentation

As this is forked from Primer, most components are the same as the ones listed on their website. When we make major changes, we will update this repository accordingly.

## Install
This repository is distributed with [npm]. After [installing npm][install-npm], you can install `@evetv/css` with this command:

```sh
npm install --save @evetv/css
```

## Usage
The included source files are written in [Sass] using SCSS syntax. After [installing](#install) with npm, you can add your project's `node_modules` directory to your Sass [include paths](https://github.com/sass/node-sass#includepaths) (AKA [load paths](http://technology.customink.com/blog/2014/10/09/understanding-and-using-sass-load-paths/) in Ruby), then import it like this:

```scss
@import '@evetv/css';
```

You can import individual Mahogany modules directly from the `@evetv/css` package:

```scss
@import '@evetv/css/core';
@import '@evetv/css/product';
@import '@evetv/css/marketing';
```

## Development
See [DEVELOP.md](DEVELOP.md) for development docs.

## Releasing (for Eve staff)
You can find docs about our release process in [RELEASING.md](RELEASING.md).

## License

[MIT](./LICENSE) &copy; [Eve](https://github.com/evetv)

[install-npm]: https://docs.npmjs.com/getting-started/installing-node
[npm]: https://www.npmjs.com/
[primer]: https://primer.style/
[sass]: http://sass-lang.com/

# Developers Release

[![Build Status][travis-image]][travis-url] [![dependency status][dep-image]][dep-url]

This repository contains the [Vapory Developers](https://developers.vapory.org/) website.

## Prerequisite
* node
* npm

## Installation
Make sure you have node.js and npm installed.

Clone the repository and install the dependencies

```bash
git clone https://github.com/vaporyco/vaporyco.github.io
cd vaporyco.github.io
npm install
npm install -g grunt-cli
```

## Build static resources

```bash
grunt
```

## Run

```bash
npm start
```

see the interface at http://localhost:3000

## Publish latest master to GitHub Pages

```
git checkout gh-pages
git merge develop
grunt build
git commit -am "Updated build"
git push origin gh-pages
```

[travis-image]:https://travis-ci.org/ethereum/ethereum-org.svg
[travis-url]: https://travis-ci.org/ethereum/ethereum-org
[dep-image]: https://david-dm.org/ethereum/ethereum-org.svg
[dep-url]: https://david-dm.org/ethereum/ethereum-org

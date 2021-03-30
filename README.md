<h1 align="center" style="position: relative;">
    <img width="200" src="./docs/nodarkreader.png"/><br>
    NoDarkreader
</h1>

<h4 align="center">
    A workaround to block the Darkreader extension from working on your already dark website!
</h4>

<p align="center">
    <img alt="npm" src="https://img.shields.io/npm/v/no-darkreader"/>
    <img alt="GitHub" src="https://img.shields.io/github/license/hadialqattan/no-darkreader">
    <a href="https://deepscan.io/dashboard#view=project&tid=13457&pid=16463&bid=353863"><img src="https://deepscan.io/api/teams/13457/projects/16463/branches/353863/badge/grade.svg" alt="DeepScan grade"></a>
    <img alt="GitHub file size in bytes" src="https://img.shields.io/github/size/hadialqattan/no-darkreader/nodarkreader.min.js?label=minified%20size">
</p>

<p align="center">
    <a href="#installation">Installation</a> •
    <a href="#usage">Usage</a> •
    <a href="#contributing">Contributing</a> •
    <a href="#license">License</a>
</p>

## Installation

You can copy the latest minified version from [here](https://raw.githubusercontent.com/hadialqattan/no-darkreader/master/nodarkreader.min.js).

You can also install the package via `npm`:

```sh
npm install no-darkreader
```

## Usage

Setup your `index.html` file, then it should work properly:

```html
...
<head>
  ...
  <meta name="darkreader" content="DISABLE-DARKREADER-WORKAROUND" />
  ...
</head>
...
<script src="./path/to/nodarkreader.min.js"></script>
...
```

Or if it installed via `npm` you can add the line bellow in your `index.html`:

```html
<meta name="darkreader" content="DISABLE-DARKREADER-WORKAROUND" />
```

and the line bellow in your app entrypoint file (e.g. `index.js` or `App.js` ):

```js
import 'no-darkreader'
```

## Contributing

> note: please run `./minify.sh` before submitting any PR!

Pull requests are welcome! For larger changes, especially structural ones, please open an issue first to discuss what you would like to change.

If you have a feature request, feel free to [open an issue](https://github.com/hadialqattan/no-darkreader/issues)!

## License

This project is licensed under a [MIT](./LICENSE) license.

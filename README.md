> We highly suggest starting using https://github.com/artf/grapesjs-cli for your new plugin projects

# GrapesJS Plugin Boilerplate


<span><a href="https://david-dm.org/artf/grapesjs-plugin-boilerplate#info=devDependencies" title="View the status of this project's development dependencies on DavidDM"><img src="https://img.shields.io/david/dev/artf/grapesjs-plugin-boilerplate.svg" alt="Dev Dependency Status" /></a></span>

This boilerplate helps you quickly start a production ready plugin for GrapesJS. If you don't know from where to start, check this guide [Creating plugins](https://grapesjs.com/docs/modules/Plugins.html). Sections below are also used as boilerplate for your README, follow these steps below

### Usage
1. Clone this repository `git clone https://github.com/pepiuox/grapesjs-bootstrap-elements.git`
1. Replace in all files `grapesjs-bootstrap-elements` and `grapesjs-plugin-boilerplate` with your plugin name.
  **The name of your plugin depends on the `name` key in your `package.json`**
1. Update all the data in `package.json`
1. Install dependencies `npm i` and run the local server `npm start`
1. Start creating your plugin from `src/index.js`
1. Show some gif/demo if possible
1. Update README
1. When you're ready, build your source with `npm run build`
1. Publish




## Summary

* Plugin name: `grapesjs-bootstrap-elements`
* Components
  * `new-component1`
  * `new-component2`
* Blocks
  * `new-block1`
  * `new-block1`
...





## Options

|Option|Description|Default|
|-|-|-
|`option1`|Description option|`default value`|





## Download

* CDN
  * `https://unpkg.com/grapesjs-bootstrap-elements`
* NPM
  * `npm i grapesjs-bootstrap-elements`
* GIT
  * `git clone https://github.com/pepiuox/grapesjs-bootstrap-elements.git`





## Usage

Directly in the browser
```html
<link href="https://unpkg.com/grapesjs/dist/css/grapes.min.css" rel="stylesheet"/>
<script src="https://unpkg.com/grapesjs"></script>
<script src="path/to/grapesjs-bootstrap-elements.min.js"></script>

<div id="gjs"></div>

<script type="text/javascript">
  var editor = grapesjs.init({
      container : '#gjs',
      // ...
      plugins: ['grapesjs-bootstrap-elements'],
      pluginsOpts: {
        'grapesjs-bootstrap-elements': { /* options */ }
      }
  });
</script>
```

Modern javascript
```js
import grapesjs from 'grapesjs';
import yourPluginName from 'grapesjs-bootstrap-elements';

const editor = grapesjs.init({
  container : '#gjs',
  // ...
  plugins: [grapesjs-bootstrap-elements],
  pluginsOpts: {
    [grapesjs-bootstrap-elements]: { /* options */ }
  }
  // or
  plugins: [
    editor => grapesjs-bootstrap-elements(editor, { /* options */ }),
  ],
});
```





## Development

Clone the repository

```sh
$ git clone https://github.com/pepiuox/grapesjs-bootstrap-elements.git
$ cd grapesjs-bootstrap-elements
```

Install dependencies

```sh
$ npm i
```

Start the dev server

```sh
$ npm start
```





## License

BSD 3-Clause

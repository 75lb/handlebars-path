[![view on npm](http://img.shields.io/npm/v/handlebars-path.svg)](https://www.npmjs.org/package/handlebars-path)
![npm module downloads per month](http://img.shields.io/npm/dm/handlebars-path.svg)
[![Dependency Status](https://david-dm.org/75lb/handlebars-path.png)](https://david-dm.org/75lb/handlebars-path)

handlebars-path
===============
Helper mappings for the node.js [path module](http://nodejs.org/api/path.html).

* path-normalize
* path-join
* path-resolve
* path-relative
* path-basename
* path-extname

###Examples
For example, the template
```
Filename: {{path-basename "parsnip.veg" ".veg"}}.txt
```
returns
```
Filename: parsnip.txt
```
etc.
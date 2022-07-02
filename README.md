# QuidPHP/Include
[![Release](https://img.shields.io/github/v/release/quidphp/include)](https://packagist.org/packages/quidphp/include)
[![License](https://img.shields.io/github/license/quidphp/include)](https://github.com/quidphp/include/blob/master/LICENSE)
[![Code Size](https://img.shields.io/github/languages/code-size/quidphp/include)](https://github.com/quidphp/include)

## About
**QuidPHP/Include** contains third-party front-end scripts. These scripts are used by Lemur CMS.

## License
**QuidPHP/Include** is available as an open-source package under the [MIT license](LICENSE).

## Installation
**QuidPHP/Include** can be easily installed with [Composer](https://getcomposer.org). It is available on [Packagist](https://packagist.org/packages/quidphp/site).
``` bash
$ composer require quidphp/include
```
Once installed, the package will be available within your *vendor* folder.

## Requirement
**QuidPHP/Include** requires any modern browser (not Internet Explorer).

## Included
**QuidPHP/Include** comes bundled with the following front-end packages:
- [Financial-Times/polyfill-service](https://github.com/Financial-Times/polyfill-service) - Polyfill.io - Automatic polyfill service, used for Internet Explorer and Microsoft Edge. [jonathantneal/element-qsa-scope](https://github.com/jonathantneal/element-qsa-scope), a polyfill for query selector scope, is also manually copied within the polyfill file.
- [SortableJs/Sortable](https://github.com/SortableJS/Sortable) - Sortable - A JavaScript library for reorderable drag-and-drop lists on modern browsers and touch devices
- [tinymce/tinymce](https://github.com/tinymce/tinymce) - Tinymce - French language pack for Tinymce

## Overview
**QuidPHP/Include** contains 3 JavaScript files. Here is an overview:
- [fr_Fr](src/tinymce/langs/fr_Fr.js) - French language pack for the Tinymce text editor
- [polyfill](src/polyfill.js) - Polyfill script used by Lemur CMS, targets earlier version of Microsoft Edge
- [sortable](src/sortable.js) - Minified copy of the Sortable JavaScript library
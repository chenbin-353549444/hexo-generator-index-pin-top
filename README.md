# hexo-generator-index-updated

[![Build Status](https://travis-ci.org/hexojs/hexo-generator-index.svg?branch=master)](https://travis-ci.org/hexojs/hexo-generator-index)  [![NPM version](https://badge.fury.io/js/hexo-generator-index.svg)](http://badge.fury.io/js/hexo-generator-index) [![Coverage Status](https://img.shields.io/coveralls/hexojs/hexo-generator-index.svg)](https://coveralls.io/r/hexojs/hexo-generator-index?branch=master)

Index generator for [Hexo], Sort by `top and updated`

## Installation

``` bash
$ npm uninstall hexo-generator-index --save
$ npm install hexo-generator-index-updated --save
```

## Feautres
This version supports pin-top feature, you can add the `top: True` field to post's front-matter to pin it.

## Options
Add or modify the following section to your root _config.yml file

``` yaml
index_generator:
  path: ''
  per_page: 10
  order_by: -updated
```

- **path**: Root path for your blogs index page. (default = '')
- **per_page**: Posts displayed per page. (0 = disable pagination)
- **order_by**: Posts order. (Order by `-updated` or `-date`)

## License

MIT

[Hexo]: http://hexo.io/

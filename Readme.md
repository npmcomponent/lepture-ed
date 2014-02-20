*This repository is a mirror of the [component](http://component.io) module [lepture/ed](http://github.com/lepture/ed). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/lepture-ed`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
# ed

A simple yet functional editor without configuration. **WIP**

I am sorry that you can't customize anything! And you will never be able
to customize anything. I won't add any more buttons on the toolbar.

## Installation

Install with [component(1)](http://component.io):

    $ component install lepture/ed

## API

```js
var ed = require('ed')
ed(document.querySelectory('#editor'), {
  path: '/upload'
})
```

### Options

All options are related to image uploading.

1. **path**: upload url path
2. **headers**: extra headers for your image server
3. **data**: extra body data for your image server

### .value()

```js
var html = ed.value()
```

Get sanitized html of the content.

## License

MIT

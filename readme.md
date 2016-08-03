## Clipboard manager for Zazu

[![Build Status](https://travis-ci.org/tinytacoteam/zazu-clipboard.svg?branch=master)](https://travis-ci.org/tinytacoteam/zazu-clipboard)

Remembers the things you've copied into your clipboard, and gives it back in a
searchable format.

## Installing

Add the package to your plugins array in `./zazurc.js`.

~~~ javascript
'tinytacoteam/zazu-clipboard',
~~~

You can overwrite the keyboard shortcut by defining a variable with the name
`ClipboardKey`.

~~~ javascript
{
  name: 'tinytacoteam/zazu-clipboard',
  variables: {
    ClipboardKey: 'cmd+shift+v',
  },
}
~~~

If you prefer to disable image storing, you can set the `ignoreImages` to
`true`.

~~~ javascript
{
  name: 'tinytacoteam/zazu-clipboard',
  variables: {
    ignoreImages: true,
  },
}
~~~

## Screenshots

![text](./assets/text_screenshot.png)

![color](./assets/color_screenshot.png)

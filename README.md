# volto-block-style
[![Releases](https://img.shields.io/github/v/release/eea/volto-block-style)](https://github.com/eea/volto-block-style/releases)

[Volto](https://github.com/plone/volto) add-on

## Features

A generic framework to style blocks and other components.

To configure it, set `settings.pluggableStylesBlocksWhitelist` as a list of
block types that you want to enable. By default it is enabled for all blocks.

Ideally it should be loaded as the last addon in Volto project configuration.

###

![Screenshot](./screenshot.png)

## Getting started

1. Create new volto project if you don't already have one:
    ```
    $ npm install -g @plone/create-volto-app
    $ create-volto-app my-volto-project
    $ cd my-volto-project
    ```

1. Update `package.json`:
    ``` JSON
    "addons": [
        "@eeacms/volto-block-style"
    ],

    "dependencies": {
        "@eeacms/volto-block-style": "github:eea/volto-block-style#1.0.0"
    }
    ```

1. Install new add-ons and restart Volto:
    ```
    $ yarn
    $ yarn start
    ```

1. Go to http://localhost:3000

1. Happy editing!

## How to contribute

See [DEVELOP.md](https://github.com/eea/volto-block-style/blob/master/DEVELOP.md2).

## Copyright and license

The Initial Owner of the Original Code is European Environment Agency (EEA).
All Rights Reserved.

See [LICENSE.md](https://github.com/eea/volto-block-style/blob/master/LICENSE.md) for details.

## Funding

[European Environment Agency (EU)](http://eea.europa.eu)

# Git Node module [![Build Status](https://travis-ci.org/atom/node-git.png)](https://travis-ci.org/atom/node-git)

Helpers for working with Git repositories built natively on top of
[libgit2](http://libgit2.github.com).

## Installing

```sh
npm install git-utils
```

## Building
  * Clone the repository
  * Run `npm install`
  * Run `grunt` to compile the native and CoffeeScript code

## Documentation

### git.open(path)

```coffeescript
git = require 'git-utils'

repository = git.open('/Users/me/repos/node')
```

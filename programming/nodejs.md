# [Nodejs](https://nodejs.org)

As of 2019 this is still my favorite language to write

## Cleanup

Remove all `node_modules` folders recursively.  A `node_modules` folder can take up a lot of space on your laptop over time, and it can be useful to delete them periodically.

```bash
find . -name 'node_modules' -type d -prune -exec rm -rf '{}' +
```

## Installing Node

### nvm

The easiest way to get started with nodejs is to install it with [nvm](https://github.com/nvm-sh/nvm)

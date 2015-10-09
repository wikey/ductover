# ductover

[![Build Status](https://travis-ci.org/garrison/ductover.svg)](https://travis-ci.org/garrison/ductover)

To build:

    $ npm install
    $ ./node_modules/.bin/bower install
    $ ./node_modules/.bin/bower install shuffle-array
    $ ./watch-jsx

Then navigate to `index.html` in a web browser.

## Debian install notes

In Debian the `node` binary is named `nodejs` so you will need to run `ln -s /usr/bin/nodejs /usr/local/bin/node` before `bower install`.

# Polymer Intro project

This project contains some explorations of component generation functionality provided by [Polymer 1.0](https://www.polymer-project.org/1.0/). 

## Included Elements
 * `two-way-binder` - Binds data between `input` element and `p` element content
 * `code-viewer` - Accepts code as input in `textarea` and then reproduces code, properly highlighted, below. Also allows for `textarea` and highlighted code to be cleared.

## How to Run
 * pull down bower dependencies
  * `bower install`
 * install `http-server` or another way to serve static files
  * `npm i http-server -g`
 * type `http-server` at command line while in repository directory and load `http://127.0.0.1:8080/` into browser

Yeoman generator that scaffolds out a Zurb Foundation 5 web app.

[![NPM](https://nodei.co/npm/generator-foundation-five.png?downloads=true)](https://nodei.co/npm/generator-foundation-five/)
[![NPM version](https://badge.fury.io/js/generator-foundation-five.png)](http://badge.fury.io/js/generator-foundation-five)
[![Dependency Status](https://david-dm.org/bauschan/generator-foundation-five.png)](https://david-dm.org/bauschan/generator-foundation-five)


## Before you begin

1. Install Node (with npm): http://nodejs.org/#download
2. Install Sass: http://sass-lang.com/download.html 
3. Install Compass: http://compass-style.org/

## Usage

- Install it (only once): `npm install -g generator-foundation-five`

- Create a new folder and cd into it: `mkdir foundation-project && cd $_`

- Run `yo foundation-five`

- Run `bower install`

- Run `grunt` to build and `grunt serve` to preview

- Run `grunt dalek` to execute cross browser tests with [dalekjs](http://dalekjs.com/)



## Options

* `--skip-install`

  Skips the automatic execution of `bower` and `npm` after
  scaffolding has finished.

* `--test-framework=[framework]`

  Defaults to `mocha`. Can be switched for
  another supported testing framework like `jasmine`.



## License

[BSD license](http://opensource.org/licenses/bsd-license.php)
# generator-react-gulp-browserify [![Build Status](https://secure.travis-ci.org/randylien/generator-react-gulp-browserify.png?branch=master)](https://travis-ci.org/randylien/generator-react-gulp-browserify)

> [Yeoman](http://yeoman.io) generator for facebook's React framework - Integrate with gulp and browserify.

## What's new?

* Add watchify support
* Use browserify extension instead of gulp extension
* Autorun `bower install` & `npm install` by default


## What's inside?

* gulp
* browserify
* reactify - Help to transform JSX
* coffeescript
* bootstrap-sass-official - twitter bootstrap official Sass version
* jade - html template
* livereload
* watchify support!
* Jest support!

## Getting Started

### Install Yeoman

```
$ npm install -g yo
```

### Install and use Generators

To install generator-react-gulp-browserify from npm, run:

```
$ npm install -g generator-react-gulp-browserify
```

Finally, initiate the generator:

```
$ yo react-gulp-browserify
```

### Install Sass

```
$ gem install sass
```

If you find your css build results are empty, update your sass gem.

### Run task

Run watch task and begin to develop your React components.

```
$ gulp watch
```

## License

MIT

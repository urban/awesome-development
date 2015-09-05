# Awesome Development

> A curated list of [packages](#pakcages) and [resources](#resources) that I find useful for development.

Inspired by the [awesome](https://github.com/sindresorhus/awesome) list thing by [Sindre Sorhus](http://sindresorhus.com) and [Essential JavaScript Links](https://github.com/ericelliott/essential-javascript-links) by [Eric Elliott](https://github.com/ericelliott).


## Packages

- [Package managers](#package-managers)
- [Build tools](#build-tools)
- [Command-line apps](#command-line-apps)
- [Functional programming](#functional-programming)
- [HTTP](#http)
- [Web frameworks](#web-frameworks)
- [Command-line utilities](#command-line-utilities)
- [Hardware](#hardware)
- [Templating](#templating)
- [Documentation](#documentation)
- [Filesystem](#filesystem)
- [Control flow](#control-flow)
- [Streams](#streams)
- [Real-time](#real-time)
- [Date](#date)
- [Image](#image)
- [Text](#text)
- [Math](#math)
- [Data validation](#data-validation)
- [Parsing](#parsing)
- [Humanize](#humanize)
- [Compression](#compression)
- [Network](#network)
- [Static site generators](#static-site-generators)
- [Content management systems](#content-management-systems)
- [Forum](#forum)
- [Blogging](#blogging)
- [Database](#database)
- [Testing](#testing)
- [Benchmarking](#benchmarking)
- [Minifiers](#minifiers)
- [Authentication](#authentication)
- [Node.js management](#nodejs-management)
- [Email](#email)
- [Polyfills](#polyfills)
- [Natural language processing](#natural-language-processing)
- [Process management](#process-management)
- [AST](#ast)
- [Miscellaneous](#miscellaneous)


### Package managers

- [Bower](http://bower.io) - A package manager for the web.
- [npm](https://github.com/npm/npm/) - A package manager for Node.js and the web.


### Build tools

- [babel]()
    + [babel-core]()
- [browserify](https://github.com/substack/node-browserify) - Browser-side require() the Node.js way.
- [gulp.js](http://gulpjs.com) - Streaming and fast build system that favors code over config.
    + [gulp-changed]()
    + [gulp-concat]()
    + [gulp-concat]()
    + [gulp-data]()
    + [gulp-if]()
    + [gulp-load-plugins]()
    + [gulp-rename]()
    + [gulp-sourcemaps]()
    + [gulp-util]()
- [PostCSS](https://github.com/postcss/postcss) - Framework for CSS postprocessors, to modify CSS.
    + [autoprefixer-core]()
    + [csswring]()
- [webpack](https://github.com/webpack/webpack) - Packs CommonJS/AMD modules for the browser.
    + [babel-loader]()
    + [extract-text-webpack-plugin]()
    + [postcss-loader]()
    + [sass-loader]()
    + [url-loader]()


### Command-line apps

- [http-server](https://github.com/nodeapps/http-server) - Simple, zero-config command-line HTTP server.
- [standard](https://github.com/feross/standard) - JavaScript Standard Style.


### Functional programming

- [immutable](https://github.com/facebook/immutable-js) - Immutable data collections.
- [lodash](http://lodash.com) - A utility library delivering consistency, customization, performance, & extras. A better and faster Underscore.js.


### HTTP

- [nets](https://github.com/maxogden/nets) - HTTP client that works in node and browsers.
- [request](https://github.com/mikeal/request) - Simplified HTTP request client.
- [superagent](https://github.com/visionmedia/superagent) - A small progressive HTTP request library.


### Web frameworks

- [Koa](http://koajs.com) - A new web framework designed by the team behind Express, which aims to be a smaller, more expressive, and more robust foundation for web applications and APIs.
- [Restify](http://mcavage.me/node-restify/) - A node framework built specifically to enable you to build correct REST web services.


### Command-line utilities

- [chalk](https://github.com/sindresorhus/chalk) - Terminal string styling done right.
- [Inquirer.js](https://github.com/SBoudrias/Inquirer.js) - Interactive command-line prompt.


### Hardware

- [johnny-five](https://github.com/rwaldron/johnny-five) - Firmata based Arduino Framework.
- [serialport](https://github.com/voodootikigod/node-serialport) - Access serial ports for reading and writing.
- [cylon.js](http://cylonjs.com/) - Next generation robotics framework with support for 26 different platforms.
- [onoff](https://github.com/fivdi/onoff) GPIO access and interrupt detection with Node.js.

### Templating

- [handlebars.js](https://github.com/wycats/handlebars.js/) - A superset of Mustache templates which adds powerful features like helpers and more advanced blocks.


### Documentation

- [dox](https://github.com/visionmedia/dox) - JavaScript documentation generator using Markdown and JSDoc.


### Filesystem

- [del](https://github.com/sindresorhus/del) - Delete files/folders using globs.
- [globby](https://github.com/sindresorhus/globby) - Glob files with support for multiple patterns.
- [cpy](https://github.com/sindresorhus/cpy) - Copy files.
- [rimraf](https://github.com/isaacs/rimraf) - Recursively delete files like `rm -rf`.
- [mkdirp](https://github.com/substack/node-mkdirp) - Recursively create directories like `mkdir -p`.
- [fs-extra](https://github.com/jprichardson/node-fs-extra) - Extra methods for the `fs` module.
- [look-up](https://github.com/jonschlinkert/look-up) - Find the first file matching a given pattern in the current directory or the nearest ancestor directory.


### Control flow

- Callbacks
    + [async](https://github.com/caolan/async) - Provides straight-forward, powerful functions for working with asynchronousity.
- Generators
    + [co](https://github.com/visionmedia/co) - The ultimate generator based flow-control goodness.
- Promises
    + [Bluebird](https://github.com/petkaantonov/bluebird) - A fully featured promise library with focus on innovative features and performance.


### Streams

- [through2](https://github.com/rvagg/through2) - Tiny wrapper around streams2 Transform to avoid explicit subclassing noise.
- [concat-stream](https://github.com/maxogden/concat-stream) - Concatenates a stream into strings or binary data.
- [co-stream](https://github.com/juliangruber/co-stream) - [co](https://github.com/visionmedia/co) generator stream.


### Real-time

- [Socket.io](http://socket.io) - Enables real-time bidirectional event-based communication.


### Date

- [Moment.js](http://momentjs.com) - Parse, validate, manipulate, and display dates.
- [Moment Timezone](http://momentjs.com/timezone/) - IANA Time Zone Database + Moment.js.


### Image

...


### Text

- [camelcase](https://github.com/sindresorhus/camelcase) - Convert a dash/dot/underscore/space separated string to camelCase: foo-bar → fooBar.
- [normalize-url](https://github.com/sindresorhus/normalize-url) - Normalize a URL.
- [humanize-url](https://github.com/sindresorhus/humanize-url) - Humanize a URL: http://sindresorhus.com → sindresorhus.com.


### Math

...


### Data validation

...


### Parsing

- [marked](https://github.com/chjj/marked) - A markdown parser and compiler built for speed.
- [csv-parser](https://github.com/mafintosh/csv-parser) - Streaming CSV parser that aims to be faster than everyone else.


### Humanize

...


### Compression

...


### Network

...


### Static site generators

- [Metalsmith](http://www.metalsmith.io) - An extremely simple, pluggable static site generator.


### Content management systems

...

### Forum

...


### Blogging

...


### Database

- Drivers
    - [LevelUP](https://github.com/rvagg/node-levelup) - LevelDB.
    - [MongoDB](https://github.com/mongodb/node-mongodb-native) - MongoDB driver.


### Testing

- [tape](https://github.com/substack/tape) - [TAP](http://testanything.org)-producing test harness.
- [Mocha](http://mochajs.org/) - A feature-rich test framework making asynchronous testing simple and fun.

### Benchmarking

...


### Minifiers

- [UglifyJS2](http://lisperator.net/uglifyjs/) - JavaScript minifier.
- [clean-css](https://github.com/GoalSmashers/clean-css) - CSS minifier.


### Authentication

- [Passport](http://passportjs.org) - Simple, unobtrusive authentication.
- [Grant](https://github.com/simov/grant) - OAuth middleware for Express, Koa and Hapi.


### Node.js management

- [nvm](https://github.com/creationix/nvm) - Simple bash script to manage multiple active node.js versions.
- [nvm for Windows](https://github.com/coreybutler/nvm-windows) - Version management for Windows.


### Email

...


### Polyfills

- JavaScript
    - [object-assign](https://github.com/sindresorhus/object-assign) - ES6 `Object.assign()` ponyfill.
    - [es6-shim](https://github.com/paulmillr/es6-shim) - Collection of ES6 polyfills.
    - More ES6 polyfills at [es6-tools](https://github.com/addyosmani/es6-tools#polyfills).
    - [fastclick](https://github.com/ftlabs/fastclick) - Removes click delays on browsers with touch UIs.


### Natural language processing

...


### Process management

- [nodemon](https://github.com/remy/nodemon) - Monitor for any changes in your node.js application and automatically restart the server.


### AST

- [Acorn](https://github.com/marijnh/acorn/) - A tiny, fast JavaScript parser.


### Miscellaneous

- [semver](https://github.com/isaacs/node-semver) - [semver](http://semver.org) parser.
- [Electron](https://github.com/atom/electron) - Build cross platform desktop apps with web technologies. *(You might like [awesome-electron](https://github.com/sindresorhus/awesome-electron))*


## Resources

...

## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Urban Faubion](http://urbanfaubion.com) has waived all copyright and related or neighboring rights to this work.

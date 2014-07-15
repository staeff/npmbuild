# npm as build-tool

This repo represents code that is covered in the article http://blog.ponyfoo.com/2014/07/04/choose-grunt-gulp-or-npm.

It is about how to use npm as a build-tool. Further the article compares npm with grunt and gulp. But this repo shows
only how to work with npm as a build-tool.

## How to use it

* the build task runs the following steps:
  * remove old dist-folder (clean)
  * re-create to dist-folder structure (build-dist)
  * check javascript with jshint (hintjs)
  * concatenate javascript-files into dist/js/app.js (concatjs)
  * transform stylus file to css (build-css)
  * concatenate css-files into dist/css/style.css (concatcss)

    
    $ npm run build

* the emoji-task shows how to configure and run a local script
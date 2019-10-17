# Gulp Starter  

This repo is a gulp starter using NPM package manager.

Remember to do run the `npm install` command after cloning this repo :) 

This starter includes: 

`gulp-sass` : compiles Sass to CSS in Gulp

`gulp watch` : method that checks to see if a file was saved

`Browser Sync` : makes Gulp reload the browser whenever we save a file

`useref` : concatenates any number of CSS and JavaScript files into a single file by looking for a comment that starts with "<!--build:" and ends with "<!--endbuild-->"

`gulpIf` : Conditionally run a task

`uglify` : plugin to help with minifying JavaScript files

`cssnano` : minify the concatenated CSS file

`gulp-imagemin` : helps optimize images

`gulp-cache` : to help optimize images when necessary and cache the rest - reduces slow process

`del` : cleaning (or in simpler terms, deleting files) - only affects the dist folder

`runSequence` : allows you to run tasks in a set sequence and simultaneously if placed in an array

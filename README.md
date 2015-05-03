# gulp-extify [![Build Status][travis-image]][travis-url]
> An extjs-dependency plugin for gulp 3

## Usage

First, install `gulp-extify` as dependency:

```shell
npm install --save gulp-extify
```

Then, add it to your `gulpfile.js`:

```javascript
var extify = require('gulp-extify');

gulp.task('scripts', function(){
  gulp.src(['app/**/*.js'])
    .pipe(extify())
    .pipe(concat('scripts.js'))
    .pipe(gulp.dest('./build/'))
});
```


## API

gulp-extify can be used to reorder your gulp.src files.

### extify([, options])

#### options
Type: `Object`

Coming soon

[travis-url]: https://travis-ci.org/sebarth/gulp-extify
[travis-image]: https://travis-ci.org/sebarth/gulp-extify.svg?branch=master
[npm-url]: Coming soon
[npm-image]: Coming soon

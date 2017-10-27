# A fork from [gulp](https://github.com/creative/gulp-tinypng)-tinypng

> Minify PNG and JPG using the [tinypng](https://tinypng.com/) API



## Install

Install with [npm](https://npmjs.org/package/gulp-tinypng)

```
npm install --save-dev gulp-tinypng
```


## Example

```js
var gulp = require('gulp');
var tinypng = require('gulp-tinypng');

gulp.task('tinypng', function () {
	gulp.src('src/**/*.png')
		.pipe(tinypng('API_KEY'))
		.pipe(gulp.dest('compressed_images'));
});
```


## API
Get your own free [API](https://tinypng.com/developers)-key at [tinify.com](https://tinypng.com/developers).

### tinypng(options)


## License

MIT © [Gaurav Jassal](http://gaurav.jassal.me)

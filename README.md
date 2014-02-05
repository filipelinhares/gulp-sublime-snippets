#[Gulp](http:www.gulpjs.com) Snippets for Sublime Text

![Gulp Snippets](https://imagizer.imageshack.us/v2/800x307q90/842/1dl6.jpg)

##Even more. Speed. Efficiency. Simplicity.
---

###vargulp
`var gulp = require('gulp-name');`


###pipe
`.pipe(name('file'))`

###gulps - [Docs](https://github.com/gulpjs/gulp/blob/master/docs/API.md#gulpsrcglobs-options)
```
gulp.src('scriptFiles')
  .pipe(name('file'))
```

###gulpt - [Docs](https://github.com/gulpjs/gulp/blob/master/docs/API.md#gulptaskname-deps-fn)
```
gulp.task('name',['tasks'], function() {
    // content
});
```

###gulpd - [Docs](https://github.com/gulpjs/gulp/blob/master/docs/API.md#gulpdestpath)
```
.pipe(gulp.dest('folder'));
```

###gulpw - [Docs](https://github.com/gulpjs/gulp/blob/master/docs/API.md#gulpwatchglob-opts-tasks)
`gulp.watch('file', ['tasks']);`

###gulpwcb - [Docs](https://github.com/gulpjs/gulp/blob/master/docs/API.md#gulpwatchglob-opts-cb)
```
gulp.watch('file'}, function(event) {
  console.log(' File '+event.path+' was '+event.type+', running tasks...');
});
```


#####Update - Just Remove and Install again.
#Gulp Snippets for Sublime Text [![BuildStatus](https://travis-ci.org/FilipeLinhares/gulp-sublime-snippets.png?branch=master)](https://travis-ci.org/FilipeLinhares/gulp-sublime-snippets)

###vargulp
`var gulp = require('gulp-name');`

###gulpd
```
gulp.task('name', function() {
    // content
}
```

###gulps
```
gulp.src('scriptFiles')
  .pipe(name('file'))
```

###pipe
`.pipe(name('file'))`

###gulpw
```
gulp.watch('files/folder', function(event){
  //content
});
```

###gulpr
`gulp.run('name');`

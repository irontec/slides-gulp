### ¿Cómo funciona?

<div class='span5 column'>
![](assets/gulp-flow.png)
</div>

<div class='span7 column' style="margin-top: 100px; margin-left: 20px; text-align: left;">
    <pre>
        <code>
gulp.src('js/*.js')
    .pipe(concat('script.min.js'))
    .pipe(uglify())
    .pipe(gulp.dest('js/build/'));
        </code>
    </pre>
</div>

# Custom CSS for use with Carnap

This is the custom CSS I use with <https://carnap.io>.

It is written in SASS, and it is a bit of a mess. To generate production CSS using Ruby Sass:

```
    sass sanson-book.scss:sanson-book.css --style compressed --scss
```

The code in `_exercises.scss` represents an opinionated attempt to improve the
styling of Carnap's different exercise types, and is related to
Carnap/Carnap#261



# Gulp Default Config

This is a gulp starter based on ([WPGulp](https://github.com/ahmadawais/WPGulp))

**Usage:**

>-`npx degit git@github.com:abisewski/gulp-config.git` 
>-`npm install`
>-`npm start`

Current archive paths config:

```
assets
- js
-- app
-- main.min.js
- css
-- style.scss
```

You can change folders/files path/names on `wpgulp.config.js`.

git archive --format=tar --remote=git@github.com:abisewski/gulp-config.git HEAD | tar xf -
rsync -rlp --exclude '.git' git@github.com:abisewski/gulp-config.git .

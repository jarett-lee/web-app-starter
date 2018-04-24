
# Web App Starter

A personalized web app starter.

## Features

&nbsp; &nbsp; ✓ Language - ES6+<br>
&nbsp; &nbsp; ✓ Styling - [Sass](http://sass-lang.com/)<br>
&nbsp; &nbsp; ✓ Task Runner - [Gulp](http://gulpjs.com/)<br>
&nbsp; &nbsp; ✓ Bundling - [Browserify](http://browserify.org/)<br>

## Getting Started

1. Edit package.json
  - Specifically, change the following entries:
    - name
    - description
    - repository
    - author
    - license
    - bugs
    - homepage
- Update package-lock.json and install the dependencies
```
rm package-lock.json
npm install
```

## Application Structure

```bash
├── gulp_tasks/           # Gulp tasks
├── public/               # Distribution bundle
├── src/                  # Main source folder
│   ├── js/               # JavaScript files
│   │   └── main.js       # JavaScript entry point
│   ├── main.scss         # Sass styles
│   └── index.html        # HTML entry point
├── gulpfile.js           # Gulpfile entry point
└──...                    # Configuration files
```

## Useful References

- Support es6 modules and bundles:
[link](https://web.archive.org/web/20180423230214/https://www.contentful.com/blog/2017/04/04/es6-modules-support-lands-in-browsers-is-it-time-to-rethink-bundling/)
- Gulp recipes:
[link](https://github.com/gulpjs/gulp/tree/master/docs/recipes)
  - split-tasks-across-multiple-files.md
  - browserify-transforms.md.
- Help Gulp handle errors:
  - Swallow Browserify errors:
  [link](https://gist.github.com/shovon/c876f9760c6bc74c96b4)
  - Gulp Plumber:
  [link](https://scotch.io/tutorials/prevent-errors-from-crashing-gulp-watch)

## License

The MIT License © Jarett Lee

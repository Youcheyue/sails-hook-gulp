# sails-hook-gulptask
## Purpose

This hook's responsibilities are:

#### When initialized...
+ start gulp.js
+ loads gulpfile.js in sails app path
  + run specified tasks

#### Environment
+ default: run task in (tasks/register/default.js)
+ production: run task in (tasks/register/prod.js)

## License

MIT

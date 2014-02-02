# rjs-shim

A replacement [AMD](https://github.com/amdjs/amdjs-api/wiki/AMD) loader for
[RequireJS](http://requirejs.org). It is a smaller "shim" loader, providing the
minimal AMD API footprint. It's similar to [almond](https://github.com/jrburke/almond)
but doesn't provide loader plugin support.

Another difference is that require statements are madi synchronous which is
useful if you are using require.js to build some code that is required to
execute at certain point in page loading.

## Restrictions

This shim only works with r.js builds. To see an example of real world usage
please refer to my [grunt-requirejs-karma-seed](https://github.com/grassator/grunt-requirejs-karma-seed)
project.

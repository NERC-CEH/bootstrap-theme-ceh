# CEH Theme for Bootstrap 3.2.x

A theme for CEH sites using the [Bootstrap](http://getbootstrap.com/) framework.  It has been built using [Themestrap](https://github.com/divshot/themestrap).

You can install it using bower eg.:

    bower install bootstrap-theme-ceh

## Customisation

To customise this theme, first clone the repository,

    git clone https://github.com/NERC-CEH/bootstrap-theme-ceh

Now install all the required dependencies,

    npm install
    bower install

Now you're ready to go, simply edit the `less/variables.less` and `less/theme.less` to your liking.  When you're ready, just run `grunt` and it will compile and minify the distribution for you.  You can also run `grunt watch` to automatically compile as your work.  In addition you can use `grunt serve` to run a basic web server at `http://localhost:8000` for you to check how your changes look against the `examples/kitchen-sink.html` example provided.

## Releasing a new version

Since this package is listed in the bower packages repository, to release a new version you should create a new tag in git with the new version number.  Use [semantic versioning](http://semver.org/).

## Copyright and license

Copyright 2014 Centre for Ecology & Hydrology under [the GNU Public license 2.0](LICENSE).

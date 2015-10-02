# Ubuntu Font Family

> Ubuntu Font Family Bower-ready (also SCSS-ready, LESS-ready, and plain CSS-ready)

## How to use

0. Install it from [Bower](http://bower.io/)

   ```sh
   $ bower install [--save] ubuntu-fontface
   ```

1. Import it on SCSS/LESS/CSS source code. Assuming `$BOWER_PATH=bower_components`; `$STYLE` options
are `-base`, `-condensed` and `-mono`; `$SUFFIX` options are `css`, `less`, `scss` (depending
if you're using pure CSS, [SCSS](http://sass-lang.com/), or [LESS](http://lesscss.org/).

    ```css
    @import "$BOWER_PATH/ubuntu-fontface/ubuntu$STYLE.$SUFFIX";
    ```

2. If you need any help (or have found any bug &#x1f41e;), please post it on
<a href="issues">/issues</a>. Thank you!

## License

The Ubuntu Font Family is distributed under the [Ubuntu Font Licence](http://font.ubuntu.com/licence/).

The source code in this project is distributed under the [MIT License](http://earaujoassis.mit-license.org/) &copy; Ewerton Assis

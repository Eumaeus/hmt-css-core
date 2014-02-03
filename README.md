hmt-css-core
============

Basic css styling for CITE projects and pages for the Homer Multitext

## Notes on Compiling

`css/hmt-core.css` is generated using [sass](http://sass-lang.com) on the command-line. From the project's root: `sass sass/hmt-core.scss css/hmt-core.css`. 

`test-content/test.html` is generated using [pandoc](http://johnmacfarlane.net/pandoc/). From the project's root: `pandoc -s -S -c ../css/hmt-core.css test-content/test.md -o test-content/test.html`.

## Note on including

For **citeservler**: `cp PATH/TO/hmt-css-core/css/hmt-core.css PATH/TO/cite-servlet/src/main/webapp/css/`.

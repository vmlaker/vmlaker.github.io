vmlaker.github.io
=================

My personal GitHub page `vmlaker.github.io <http://vmlaker.github.io>`_.

You're gonna need 
`Sass <http://sass-lang.com>`_ and
`Jade <http://jade-lang.com>`_:
::
 
  gem install sass
  npm install jade

Then, build the page:
::

  sass src/style.scss:style.css 
  node_modules/.bin/jade --pretty --out ./ src/index.jade

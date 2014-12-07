vmlaker.github.io
=================

My personal GitHub page `vmlaker.github.io <http://vmlaker.github.io>`_.

Download
--------

Get the source:
::

   git clone https://github.com/vmlaker/vmlaker.github.io
   cd vmlaker.github.io

Requirements
------------

Before you begin, you will need
`Sass <http://sass-lang.com>`_ and
`Jade <http://jade-lang.com>`_:
::
 
   gem install --user-install sass
   npm install jade

Build
-----

Then, build the page:
::

   sass src/style.scss:style.css 
   node_modules/.bin/jade --pretty --out ./ src/index.jade

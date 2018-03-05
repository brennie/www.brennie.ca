Powered by Sphinx
=================

.. author:: default
.. categories:: meta
.. tags:: tinkerer python sphinx

I *love* Sphinx_. I've been using it for all my Python documentation. While
writing documentation for other languages where there isn't a *de facto*
standard for documentation (which is the case with esdoc_ vs jsdoc_ vs typedoc_
vs react-docgen_ in JavaScript land) I often wish Sphinx was more wide spread
outside of Python.

I'm also a big fan of reStructuredText_, which is the language that Sphinx uses
to generate its beautiful documentation. It is very expressive and (though it
lacks some features (inability to have a ``<code>`` inside an ``<a>``, I'm
looking at you), it seems to be a very good fit for documentation most of the
time. When I have to write documentation in formats such as Markdown, I often
feel the limitations of the language.

So when I found out about Tinkerer_ I was ecstatic. Through the extensibility of
Sphinx, it is able to create an excellent static site generator. I am looking
forward to writing more content here (some of it about Tinkerer & Sphinx, I'm
sure). Static site generation is all the rage these days, and it definitely
makes sense for websites that only host static content. Running a full webserver
just to host a static blog is a lot more maintenance effort (and costs more)
than storing a website in something like Amazon S3.

I am hoping that this blog can serve as a development log of sorts, documenting
my thought process and experience as I work on open source projects. I'm also
hoping to exercise my design skills to develop a custom theme for Tinkerer to
power this website.

Stay tuned for some documentation on how I am deploying this site with Circle CI
and AWS.

.. _esdoc: https://esdoc.org
.. _jsdoc: http://jsdoc.org
.. _typedoc: http://typedoc.org
.. _react-docgen: https://github.com/reactjs/react-docgen
.. _Sphinx: http://sphinx-doc.org
.. _reStructuredText: http://docutils.sourceforge.net/rst.html
.. _Tinkerer: http://tinkerer.me

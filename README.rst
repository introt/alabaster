What is Alabester?
==================

Alabaster with some CSS bugs squashed.

However, it's not a drop-in replacement; due to Sphinx hard-coding some extra combatibility for Alabaster, your sidebar config likely won't work without modifications.

* If you'd like to know more, check out the writeup on my `bleg <https://introt.github.io/bleg>`_.

* If you want a quick fix, just put a fixed ``alabaster.css`` into the ``_static`` folder and call it a day.

* If you're feeling adventurous, [join in on the fun](https://github.com/introt/alabester/fork)!

-----

What is Alabaster?
==================

Alabaster is a visually (c)lean, responsive, configurable theme for the `Sphinx
<http://sphinx-doc.org>`_ documentation system. It is Python 2+3 compatible.

It began as a third-party theme, and is still maintained separately, but as of
Sphinx 1.3, Alabaster is an install-time dependency of Sphinx and is selected
as the default theme.

Live examples of this theme can be seen on `this project's own website
<http://alabaster.readthedocs.io>`_, `paramiko.org <http://paramiko.org>`_,
`fabfile.org <http://fabfile.org>`_ and `pyinvoke.org <http://pyinvoke.org>`_.

For more documentation, please see http://alabaster.readthedocs.io.

.. note::
    You can install the development version via ``pip install -e
    git+https://github.com/bitprophet/alabaster/#egg=alabaster``.

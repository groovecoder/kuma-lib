Developing with nose
====================

Get the code
------------

The stable branch of nose is hosted at `google code
<http://code.google.com/p/python-nose/>`__. You should clone this
branch if you're developing a plugin or working on bug fixes for nose::

  hg clone http://python-nose.googlecode.com/hg/ nose-stable

The **unstable** branch of nose is hosted at `bitbucket
<http://bitbucket.org/jpellerin/nose/>`__. You should **fork** this branch if
you are developing new features for nose. Then clone your fork, and submit
your changes as a pull request. If you just want to use unstable, you can
clone the branch::

  hg clone http://bitbucket.org/jpellerin/nose/ nose-unstable

The **python3.0** version of nose, nose3, is also hosted at bitbucket. You can
fork that branch to work on features or bug fixes for nose3. If you just want
to use it, clone the branch::

  hg clone http://bitbucket.org/jpellerin/nose3/
   
Read
----
   
.. toctree ::
   :maxdepth: 2

   plugins
   api
   contributing

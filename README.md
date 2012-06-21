processRFmatlab
===============

MATLAB functions and scripts for working with receiver functions

These are functions I wrote during my post doc at USC (2009-2011) to
work with receiver function data.  It is not any formal program, but
the codes are made available in case they might be useful for learning
about or reproducing some results.

The main idea has been to try and use as much of matlab's
functionality as possible and not to rely on a single data structure
or complicated dependencies.  The codes have undergone a number of
changes as I have been learning about matlab, receiver functions and
signal processing.  Hence, they may not work as expected.

I'm not working in this research area now, so I don't expect to use or
modify these codes much.  Still I would like to maintain them if they
are useful so I'm happy to hear if you have any comments or questions.
iainbailey@gmail.com


How to use:
-----------

The functions are in separate directories based on their general class
of function.  You will need them in your path to use them. Modify the
script processRFmatlab_startup.m then run it before using the
functions or change your own startup.m file if you want to do this
automatically.


Summary of Directories:
-----------------------

example_scripts/

> Here you find some simple examples and example real world data that
use some of the functions.

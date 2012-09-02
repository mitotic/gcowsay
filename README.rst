
cowsay ASCII art
===================================================================

gcowsay Graphic art
=====================================================================

``gcowsay`` is a simple, self-contained implementation of ``cowsay``
using the GraphTerm API. It has no direct dependence
on the GraphTerm code, relying instead on escape sequences
to access GraphTerm.

For more on ``cowsay``, see http://en.wikipedia.org/wiki/Cowsay

For more on GraphTerm, see https://github.com/mitotic/graphterm

.. code::

 Usage: gcowsay [options] word1 word2 ...
 Options:
 -h, --help            show this help message and exit
 -f, --fullwindow      Fullwindow display
 --fullpage            Fullpage display
 --popup               Display popup
 -t, --text            Plain text (ASCII) display
 -w WIDTH, --width=WIDTH    Width for ASCII display (default: 40)
 --think               cowthink, instead of cowsay
 --wait                Wait, do not quit after display
 -i IMAGE, --image=IMAGE    Alternate image file

Sample screenshot of ``gcowsay`` in action within GraphTerm:

.. figure:: https://github.com/mitotic/gcowsay/raw/master/screenshots/gcowsay1.png
   :align: center
   :width: 90%
   :figwidth: 90%


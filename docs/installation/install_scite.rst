With Scite
--------

``vs-preview`` is intended to work with an IDE that can use an integrated terminal.
One IDE that can do that is Scite.

Requirements
^^^^^^^^^^^^

The following programs must be installed before you begin:

* `Windows / Mac <https://scintilla.org/SciTE.html>`_
* `Ubuntu / debian : sudo apt install scite`_

Configuring Scite
^^^^^^^^^^^^^^^

1. Associate ``.vpy`` files with Scite
    1. Right-click a ``.vpy`` file and press ``Open with > Choose another app``
    2. Check "Always use this app to open .vpy files"
    3. Scroll down and click "More apps", then "Look for another app on this PC"
    4. Browse to your Vim install location and press "Open"


Running your script
^^^^^^^^^^^^^^^^^^^

.. note::

    The installation requires two files one is vapoursynth.properties to declare .vpy as python files (syntax hilighting) and have F5 shortcut for .vpy and ctr+1 for .py, the second .SciTEUser.properties is more for user gui opimizations

1. copy  ``vapoursynth.properties`` in the proprties folder. In linux this folder is /etc/scite 
2. copy ``.SciTEUser.properties`` to your home user directory

You can now open the VapourSynth script you want to run in Scite
and run ``vs-preview`` by pressing ``F5``.

If everything works properly,
it should open up a vs-preview

If there's an error with your script,
it will print it in the right output pane.
If your script is fine,
it will open ``vs-preview`` with the current script.

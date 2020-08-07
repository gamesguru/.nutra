**********************
 .nutra (HOME folder)
**********************

This folder exists at ``~/.nutra``, (may need to enable hidden files).

The ``db`` folder is required and should not be renamed or modified.

The ``rda`` and ``day`` folders are merely suggestions and can be deleted or renamed as desired.

To use the ``rda`` and ``day`` folders, for example run

.. code-block:: bash

    nutra day ~/.nutra/day/dog.csv --rda ~/.nutra/rda/dog-18lbs.csv

==========
Parameters
==========

The ``parameters.csv`` file allows customization of several flags.

Their names and ranges are specified below.

=====  ========  ======  ===========================================
name   default   range   notes
=====  ========  ======  ===========================================
DEBUG  0         [0, 1]  Setting to 1 prints verbose logs to screen
=====  ========  ======  ===========================================

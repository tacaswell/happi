HAPPI - Heuristic Access to Positions of Photon Instruments
===========================================================
Happi is a database to hold generic information for devices
along the LCLS photon beamline.  

This is general purpose database for PCDS to organize information on any device
along the beamline. The general structure of the Python API allows users to use
:ref:`device_label` to enter structured information into the database, while
still proivding the flexibility needed for abitrary metadata.

Before entering any information, please consult the :ref:`convention_label`
page. While the client is intelligent enough to catch certain errors
there are still standards within the group we need to uphold.

.. toctree::
   :maxdepth: 1
   :caption: Tutorial

   conventions.rst
   client.rst
   develop.rst

.. toctree::
   :maxdepth: 1
   :caption: API Documentation

   client_api.rst
   backends.rst
   containers.rst

.. toctree::
   :maxdepth: 0
   :caption: Developer Documentation

   releases.rst

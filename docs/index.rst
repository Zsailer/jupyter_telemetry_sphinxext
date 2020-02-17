.. jupyter_telemetry_sphinxext documentation master file, created by
   sphinx-quickstart on Mon Feb 17 13:10:09 2020.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

The Jupyter Telemetry Sphinx Extension
======================================

*A Sphinx extension for auto-generating Jupyter Telemetry schema documentation*


To install this extension, run:

.. code-block::

   pip install jupyter_telemetry_sphinxext


Activate the extension by adding ``jupyter_telemetry_sphinxext`` to your ``conf.py`` file.

.. code-block::


   # config.py file.

   extensions = [
      'jupyter_telemetry_sphinxext',
      ...
   ]

   # Jupyter telemetry configuration values.
   jupyter_telemetry_schema_source = "path/to/schemas/source/directory"   # Path is relative to conf.py
   jupyter_telemetry_schema_output = "path/to/output/directory"           # Path is relative to conf.py
   jupyter_telemetry_index_title = "Example Event Schemas"                # Title of the index page that lists all found schemas.


This will walk the files and directories in ``jupyter_telemetry_schema_source`` and generate restructured text pages for
any Jupyter Telemetry Event Schemas.



.. toctree::
   :maxdepth: 2
   :caption: Example pages:

   example-schemas-docs/index



Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

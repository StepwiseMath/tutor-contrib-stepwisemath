stepwisemath plugin for `Tutor <https://docs.tutor.edly.io>`__
##############################################################

stepwisemath plugin for Tutor


Installation
************

.. code-block:: bash
    python3 -m venv venv
    pip install --upgrade pip setuptools    
    pip install "tutor[full]==16.1.8"

Usage
*****

.. code-block:: bash

    tutor config save
    tutor plugins index add ./tutor_indexes
    tutor plugins update
    tutor plugins install stepwisemath 
    tutor plugins list                  # should appear
    tutor plugins enable stepwisemath
    tutor config save

License
*******

This software is licensed under the terms of the AGPLv3.

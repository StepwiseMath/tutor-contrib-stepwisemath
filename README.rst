stepwisemath plugin for `Tutor <https://docs.tutor.edly.io>`__
##############################################################

stepwisemath plugin for Tutor


Installation
************

.. code-block:: bash
    python3 -m venv venv
    pip install --upgrade pip setuptools    
    pip install "tutor[full]==16.1.8"
    pip install git+https://github.com/stepwiseMath/tutor-contrib-stepwisemath

Usage
*****

.. code-block:: bash

    tutor plugins index add ./tutor-contrib-stepwisemath/tutor_indexes/
    tutor config save
    tutor plugins update
    tutor plugins list

    tutor plugins install stepwisemath 
    tutor plugins enable stepwisemath

License
*******

This software is licensed under the terms of the AGPLv3.

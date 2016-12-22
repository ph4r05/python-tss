====================
Python TPM wrapper
====================

*pytss* is a python language wrapper for the Tspi library provided by the
TrouSerS project. libtspi is a library for interfacing with a TPM services
daemon.

Author: Matthew Garrett (matthew.garrett@nebula.com)

Installation
------------

.. code-block:: bash

    pip install pytss


Dependencies
------------

* Debian / Ubuntu
.. code-block:: bash

    sudo apt-get install tpm-tools libtspi-dev libopencryptoki-dev libssl-dev python-pip python-dev build-essential

* Redhat / Fedora
.. code-block:: bash

    sudo yum install tpm-tools opencryptoki-devel trousers-devel openssl-devel python-pip python-devel



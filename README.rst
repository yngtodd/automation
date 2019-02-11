=============================
Automation
=============================

Testing the waters of automl.

Current Libraries Explored
--------------------------

+--------------------------+------------+----------------------------------------+
| Library                  | Working    | Notes                                  |
+==========================+============+========================================+
| `Autokeras`_             | False      | |autokeras_notes|                      |
+--------------------------+------------+----------------------------------------+
| `Nascell Automl`_        | ?          | |nascell_automl_notes|                 |
+--------------------------+------------+----------------------------------------+
| `ENAS Pytorch`_          | True       | |pytorch_enas_notes|                   |
+--------------------------+------------+----------------------------------------+
| `ADANET`_                | False      | |adanet_notes|                         |
+--------------------------+------------+----------------------------------------+

.. |autokeras_notes| replace:: Cannot accept tensors less than 4D tensors
.. |nascell_automl_notes| replace:: Miraculously gives 100% accuracy on first minibatch.
.. |pytorch_enas_notes| replace:: Character level model.
.. |adanet_notes| replace:: Designed around imaging and would require considerable work for NLP.

.. _autokeras: https://autokeras.com/
.. _Nascell Automl: https://github.com/wallarm/nascell-automl
.. _ENAS Pytorch: https://github.com/carpedm20/ENAS-pytorch
.. _ADANET: https://github.com/tensorflow/adanet

Documentation
--------------
 
For references, tutorials, and examples check out our `documentation`_.

Installation
------------

From Sources:

You can either clone the public repository:

.. code-block:: console

    git clone git://github.com/yngtodd/automation

Or download the `tarball`_:

.. code-block:: console

    curl  -OL https://github.com/yngtodd/automation/tarball/master

Once you have a copy of the source, you can install it with:

.. code-block:: console

    python setup.py install

.. _tarball: https://github.com/yngtodd/automation/tarball/master
.. _documentation: https://automation.readthedocs.io/en/latest

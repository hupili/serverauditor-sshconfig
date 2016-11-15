Serverauditor ssh config utility
================================

*NOTE*: This is the quick hack very.
To install this version, simply run

```
pip install -e git+https://github.com/hupili/serverauditor-sshconfig@6adf9fbb4b8b07a935e30fc297decaac23c43b4c#egg=Package
```


Installation
------------

Serverauditor ssh config utility can be installed via `pip <http://www.pip-installer.org/en/latest/index.html>`_:

.. code-block:: bash

    $ pip install -U serverauditor-sshconfig

or `easy_install <http://pythonhosted.org/distribute/>`_:

.. code-block:: bash

    $ easy_install -U serverauditor-sshconfig


Usage
-----

If you want to *export* connections from your computer to your Serverauditor's account:

.. code-block:: bash

    $ serverauditor export

If you want to *import* connections from your Serverauditor's account to your computer:

.. code-block:: bash

    $ serverauditor import


License
-------

Please see `LICENSE <https://github.com/Crystalnix/serverauditor-sshconfig/blob/master/LICENSE>`_.


Notes
-----

* Some stages of utility's work may last for several seconds (depends on amount of the connections and your computer's performance).

* If installation failed with gcc error, you must install Python Development Libraries, for example:

.. code-block:: bash

    $ sudo apt-get install python-dev

or

.. code-block:: bash

    $ sudo yum  install python-devel.x86_64

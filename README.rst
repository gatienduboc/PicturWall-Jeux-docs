PicturWall-Jeux : Documentations
===============================================

.. image:: https://readthedocs.org/projects/picturwall-jeux-docs/badge/?version=latest
    :target: https://picturwall-jeux-docs.readthedocs.io/fr/latest/?badge=latest
    :alt: Documentation Status


Déploiement
---------------------

.. code-block:: console

    # Install required Python dependencies (Sphinx etc.)
    pip install -r docs/requirements.txt

    # Enter the Sphinx project
    cd docs/
    
    # Run the raw sphinx-build command
    sphinx-build -M html . _build/


You can also build the documentation locally with ``make``:

.. code-block:: console

    # Enter the Sphinx project
    cd docs/
    
    # Build with make
    make html
    
    # Open with your preferred browser, pointing it to the documentation index page
    firefox _build/html/index.html

Read the Docs tutorial
----------------------

To get started with Read the Docs, you may also refer to the `Read the Docs tutorial <https://docs.readthedocs.io/en/stable/tutorial/>`__.
It provides a full walk-through of building an example project similar to the one in this repository.

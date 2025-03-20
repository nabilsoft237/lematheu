.. 'mathutils' documentation master file, created by
   sphinx-quickstart on Sun Mar 16 03:02:24 2025.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.


Bienvenu dans la Documentation de Mathutils !!!!

Welcome to 'mathutils''s documentation!

=======================================

.. toctree::
   :maxdepth: 2
   :caption: Contents:



Table des matieres 
==================



.. toctree::
   :maxdepth: 2

   geometry



.. toctree::
   :maxdepth: 2

   algebra


.. toctree::
   :maxdepth: 2

   installation


.. toctree::
   :maxdepth: 2

   licence








Introduction
------------

Le package 'mathutils' est une collection de fonctions mathematiques utiles pour les d2veloppeurs Python.


Parties
-------
### geometry
le module 'geometry' fournit des fonctions pour effectuer des operations geometriques courantes.

.. autosummary::
   :toctree: generated/

   distance
   cercle_surface

### algebra
Le module 'algebra' fournit des fonctions pour effectuer des operations algebriques courantes.

.. autosummary::
   :toctree: generated/

   resoudre_equation
   determinant

installation
------------

pour installer la package 'mathutils', vous pouvez utiliser pip:

..code-block:: bash 

  pip install mathutils


sur ubuntu vous pouvez utiliser la commande :

..code-block:: bash 

  sudo apt-get install python3-mathutils  

Licence
-------
Le package 'mathutils' est distribue sous la licence MIT.

.. include:: licence.rst




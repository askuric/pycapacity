Real-time capable task-space capacity calculation python module
==================



.. image:: https://gitlab.inria.fr/auctus-team/people/antunskuric/pycapacity/-/raw/master/images/comparison.gif
  :height: 300
  :alt: Alternative text

.. image:: https://gitlab.inria.fr/auctus-team/people/antunskuric/pycapacity/-/raw/master/images/bimanual1.png
  :height: 300
  :alt: Alternative text


The ``pycapacity`` package provides a framework for the generic task-space capacity calculation for:

 *  Robotic serial manipulators - ``pycapacity.robot``
 *  Human musculoskeletal models - ``pycapacity.human``

This package also provides a module ``pycapacity.algorithms`` with a set of polytope evaluation algorithms for standard polytope formulations, that can be used as a standalone library.

Additionally, ``pycapacity.visual`` module provides a set of visualisaiton tools using the ``matplotlib`` for visualising 2d and 3d polytopes.

.. toctree::

   About <README.md>

Module contents
---------------

.. toctree::
   Robot capacity <pycapacity.robot>
   Human capacity <pycapacity.human>
   Algortihms <pycapacity.algorithms>
   Visualisation <pycapacity.visual>


.. toctree::
   :maxdepth: 2

   Coding examples <examples/index>
   

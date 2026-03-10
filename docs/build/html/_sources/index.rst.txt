.. Geometric Neural Operator documentation master file, created by
   sphinx-quickstart on Sun Mar  2 16:38:53 2025.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Overview 
=======================================

.. image:: ./geo_neural_op_software.png
   :align: center
   :width: 800

**Overview:** The *GeoNeuralOp* package provides methods
for deep learning with point-cloud manifold representations. This includes 
geometric approaches for learning differential operators, 
extracting features, shape deformations, and 
other tasks.

**Features:**

* **Curvature and Metric Estimators:** Operator training methods for 
  obtaining approximations of local
  curvatures, metrics, and geometric differential operators on
  point-clouds. 
* **PDE Neural Solvers:** Data-driven numerical methods for geometric PDEs
  on manifolds, such as Laplace-Beltrami and other problems. 
* **Dynamic Shape Deformations:** Shape evolution of point-clouds, such as
  mean-curvature driven-flows.
* **Transferable Pretrained Models:** Provides weights for models for
  use in existing data processing pipelines for estimating local 
  curvatures, Laplace-Beltrami operators, components for PDE solvers, 
  and other geometric tasks.

The package also includes variants of GNPs for efficient training 
based on factorizations and other protocols.  For more details
and pretrained models see the papers and examples below.  

**Please cite for this package:**

* **Geometric neural operators (gnps) for data-driven deep learning in
  non-euclidean settings,** B. Quackenbush, P.J. Atzberger,  Machine Learning:
  Science and Technology, 5(4), (2024),
  `<https://doi.org/10.1088/2632-2153/ad8980>`_.

**Additional papers:**

* **Transferable Foundation Models for Geometric Tasks on Point Cloud
  Representations: Geometric Neural Operators,** B. Quackenbush, P.J. Atzberger,
  Machine Learning: Science and Technology, 6(4), (2025),
  `<https://doi.org/10.1088/2632-2153/ae1bf8>`_.

* **Extending Neural Operators: Robust Handling of Functions Beyond the Training
  Set,** B. Quackenbush, P.J. Atzberger,  Machine Learning: Science and
  Technology, 6(4), (2025),
  `<https://arxiv.org/abs/2603.03621>`_.

For installation and examples, please see
`<https://github.com/atzberg/geo_neural_op>`_. 

.. toctree::
   :maxdepth: 1
   :caption: Package Reference:

   gnp.estimator
   gnp.models
   gnp.geometry
   gnp.dataset
   gnp.utils
   gnp.config


Links:
-----------------
* `GitHub for Codes / Examples`_
.. _GitHub for Codes / Examples: https://github.com/atzberg/geo_neural_op
* `Atzberger Research Group`_
.. _Atzberger Research Group: https://web.atzberger.org

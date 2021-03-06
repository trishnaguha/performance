######################################
The Python Performance Benchmark Suite
######################################

The ``performance`` project is intended to be an authoritative source of
benchmarks for all Python implementations. The focus is on real-world
benchmarks, rather than synthetic benchmarks, using whole applications when
possible.

* `performance documentation <http://pyperformance.readthedocs.io/>`_
* `performance GitHub project <https://github.com/python/performance>`_
  (source code, issues)
* `Download performance on PyPI <https://pypi.python.org/pypi/performance>`_

performance is distributed under the MIT license.

Documenation:

.. toctree::
   :maxdepth: 2

   usage
   benchmarks
   cpython_results_2017
   changelog

Other Python Benchmarks:

* CPython: `speed.python.org <https://speed.python.org/>`_ uses perf,
  performance and `Codespeed <https://github.com/tobami/codespeed/>`_ (Django
  web application)
* PyPy: `speed.pypy.org <http://speed.pypy.org/>`_
  uses `PyPy benchmarks <https://bitbucket.org/pypy/benchmarks>`_
* Pyston: `pyston-perf <https://github.com/dropbox/pyston-perf>`_
  and `speed.pyston.org <http://speed.pyston.org/>`_
* `Numba benchmarks <http://numba.pydata.org/numba-benchmark/>`_
* Cython: `Cython Demos/benchmarks
  <https://github.com/cython/cython/tree/master/Demos/benchmarks>`_
* pythran: `numpy-benchmarks
  <https://github.com/serge-sans-paille/numpy-benchmarks>`_

See also the `Python speed mailing list
<https://mail.python.org/mailman/listinfo/speed>`_ and the `Python perf module
<http://perf.readthedocs.io/>`_ (used by performance).

Image generated by bm_raytrace (pure Python raytrace):

.. image:: images/bm_raytrace.jpg
   :alt: Pure Python raytracer

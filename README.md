# pytket
[![PyPI version](https://badge.fury.io/py/pytket.svg)](https://badge.fury.io/py/pytket)
[![Documentation Status](https://readthedocs.org/projects/pytket/badge/?version=latest)](https://pytket.readthedocs.io/en/latest/?badge=latest)

`pytket` is a python module for interfacing with CQC t|ket>, a set of quantum programming tools. We currently support circuits and device architectures from both Google [Cirq](https://www.github.com/quantumlib/cirq) and [Qiskit](https://qiskit.org), allowing the t|ket> tools to be used in conjunction with projects on these platforms.

#### Getting Started
``pytket`` is available for ``python3.5`` or higher, on Linux and Macos.
To install, run 

``pip install pytket``

(we recommend using a fresh python environment).

Note, installation from source will not work, you must use pip.

See [examples/cirq_routing_example.ipynb](https://github.com/CQCL/pytket/blob/master/examples/cirq_routing_example.ipynb) for a quick introduction to using `pytket`. 

Documentation of the soure code can be found at [pytket.readthedocs.io](https://pytket.readthedocs.io)
This is a fork of the original repo for supporting our AWS image that includes these Jupuyter Notebooks.

Qutip notebooks
===============

These files are [IPython notebooks](http://ipython.org/notebook.html) for
testing different parts of QuTiP. These tests serves a somewhat different
purpose than the unit test suite that is installed as a part of QuTiP. Instead
of being small isolated (unit) tests, these notebooks are often more like
integration tests, which exercise a larger part of the QuTiP codebase to make
sure that different parts work together as expected, or tests that exercise
various related parts in a module in a single location.

To open these files, start an IPython notebook server by running the following
command in the directory that contains the files:

    $ jupyter notebook
    
or, if you have an old version of IPython installed
    
    $ ipython notebook
    
This will open a new page in your web browser, showing the IPython notebook
dashboard page with an index of all the notebooks.

Older notebooks are in v3 format. Some of the newer notebooks are in v4 format.
If you are using a version of IPython notebook that does not support v4 format.
(which would be v3.0.0 or lower), then you can convert these notebooks using:

    $ jupyter nbconvert --to notebook --nbformat 3 <nb_to_convert>
    
# Interactive online versions

This is a currently (Feb 2016) running in a beta host service binder,
which seems to running well.
[![Binder](http://img.shields.io/badge/launch-binder-ff69b4.svg?style=flat)](http://mybinder.org/repo/qutip/qutip-notebooks)
    
# Online read-only versions

You can also view the notebooks online, as read-only HTML pages rendered by
http://nbviewer.ipython.org:

# Example notebooks

 * [example-rabi-oscillations](http://nbviewer.ipython.org/urls/raw.github.com/qutip/qutip-notebooks/master/examples/example-rabi-oscillations.ipynb)
 * [example-atom-cavity-correlation-function](http://nbviewer.ipython.org/urls/raw.github.com/qutip/qutip-notebooks/master/examples/example-atom-cavity-correlation-function.ipynb)
 * [example-atom-cavity-dynamics](http://nbviewer.ipython.org/urls/raw.github.com/qutip/qutip-notebooks/master/examples/example-atom-cavity-dynamics.ipynb)
 * [example-JC-model-wigner-function](http://nbviewer.ipython.org/urls/raw.github.com/qutip/qutip-notebooks/master/examples/example-JC-model-wigner-function.ipynb)
 * [example-wigner-functions](http://nbviewer.ipython.org/urls/raw.github.com/qutip/qutip-notebooks/master/examples/example-wigner-functions.ipynb)
 * [example-trilinear](http://nbviewer.ipython.org/urls/raw.github.com/qutip/qutip-notebooks/master/examples/example-trilinear.ipynb)
 * [example-ultrastrong-coupling-groundstate](http://nbviewer.ipython.org/urls/raw.github.com/qutip/qutip-notebooks/master/examples/example-ultrastrong-coupling-groundstate.ipynb)
 * [example-landau-zener](http://nbviewer.ipython.org/urls/raw.github.com/qutip/qutip-notebooks/master/examples/example-landau-zener.ipynb)
 * [example-quantum-process-tomography](http://nbviewer.ipython.org/urls/raw.github.com/qutip/qutip-notebooks/master/examples/example-quantum-process-tomography.ipynb)
 * [example-spin-chain](http://nbviewer.ipython.org/urls/raw.github.com/qutip/qutip-notebooks/master/examples/example-spin-chain.ipynb)
 * [example-quantum-gates](http://nbviewer.ipython.org/urls/raw.github.com/qutip/qutip-notebooks/master/examples/example-quantum-gates.ipynb)
 * [example-qip-toffoli-cnot](http://nbviewer.ipython.org/urls/raw.github.com/qutip/qutip-notebooks/master/examples/example-qip-toffoli-cnot.ipynb)
 * [example-spin-chain-model](http://nbviewer.ipython.org/urls/raw.github.com/qutip/qutip-notebooks/master/examples/example-spin-chain-model.ipynb)
 * [example-qubism-and-schmidt-plots](http://nbviewer.ipython.org/urls/raw.github.com/qutip/qutip-notebooks/master/examples/example-qubism-and-schmidt-plots.ipynb)

### Bloch-Redfield master equation solver

 * [example-brmesolve](http://nbviewer.ipython.org/urls/raw.github.com/qutip/qutip-notebooks/master/examples/example-brmesolve.ipynb)
 * [example-brmesolve-steadystate](http://nbviewer.ipython.org/urls/raw.github.com/qutip/qutip-notebooks/master/examples/example-brmesolve-steadystate.ipynb)

### Two-time correlations with time-dependent Liouvillians

 * [example-pulse-wise-second-order-coherence-g2](http://nbviewer.ipython.org/urls/raw.github.com/qutip/qutip-notebooks/master/examples/example-pulse-wise-second-order-coherence-g2.ipynb)
 * [example-pulse-wise-two-photon-interference](http://nbviewer.ipython.org/urls/raw.github.com/qutip/qutip-notebooks/master/examples/example-pulse-wise-two-photon-interference.ipynb)

### Optimal control

 * [Optimal control overview](http://nbviewer.ipython.org/github/qutip/qutip-notebooks/blob/master/examples/example-optimal-control-overview.ipynb)
 * [Hadamard](http://nbviewer.ipython.org/urls/raw.github.com/qutip/qutip-notebooks/master/examples/example-control-pulseoptim-Hadamard.ipynb)
 * [Quantum Fourier Transform](http://nbviewer.ipython.org/urls/raw.github.com/qutip/qutip-notebooks/master/examples/example-control-pulseoptim-QFT.ipynb)
 * [Lindbladian](http://nbviewer.ipython.org/urls/raw.github.com/qutip/qutip-notebooks/master/examples/example-control-pulseoptim-Lindbladian.ipynb)
 * [Symplectic](http://nbviewer.ipython.org/urls/raw.github.com/qutip/qutip-notebooks/master/examples/example-control-pulseoptim-symplectic.ipynb)
 * [QFT (CRAB)](http://nbviewer.ipython.org/github/qutip/qutip-notebooks/blob/master/examples/example-control-pulseoptim-CRAB-QFT.ipynb)
 * [state to state (CRAB)](http://nbviewer.ipython.org/github/qutip/qutip-notebooks/blob/master/examples/example-control-pulseoptim-CRAB-2qubitInerac.ipynb)
 * [CNOT](http://nbviewer.ipython.org/urls/raw.github.com/qutip/qutip-notebooks/master/examples/example-control-grape-cnot.ipynb)
 * [iSWAP](http://nbviewer.ipython.org/urls/raw.github.com/qutip/qutip-notebooks/master/examples/example-control-grape-iswap.ipynb) 
 * [Single-qubit rotation](http://nbviewer.ipython.org/urls/raw.github.com/qutip/qutip-notebooks/master/examples/example-control-grape-single-qubit-rotation.ipynb)
 * [Toffoli gate](http://nbviewer.ipython.org/urls/raw.github.com/qutip/qutip-notebooks/master/examples/example-control-grape-toffoli.ipynb)

# Development notebooks

## Feature demo notebooks

 * [development-continuous-variable-test](http://nbviewer.ipython.org/urls/raw.github.com/qutip/qutip-notebooks/master/development/development-continuous-variable-test.ipynb)
 * [development-ipynbtools-test](http://nbviewer.ipython.org/urls/raw.github.com/qutip/qutip-notebooks/master/development/development-ipynbtools-test.ipynb)
 * [development-correlation-functions](http://nbviewer.ipython.org/urls/raw.github.com/qutip/qutip-notebooks/master/development/development-correlation-functions.ipynb)
 * [development-liouvillian-construction](http://nbviewer.ipython.org/urls/raw.github.com/qutip/qutip-notebooks/master/development/development-liouvillian-construction.ipynb)
 * [development-floquet-test](http://nbviewer.ipython.org/urls/raw.github.com/qutip/qutip-notebooks/master/development/development-floquet-test.ipynb)
 * [development-mcf90-test](http://nbviewer.ipython.org/urls/raw.github.com/qutip/qutip-notebooks/master/development/development-mcf90-test.ipynb)
 * [development-spectrum-test](http://nbviewer.ipython.org/urls/raw.github.com/qutip/qutip-notebooks/master/development/development-spectrum-test.ipynb)
 * [development-Qobj-extract-eliminate](http://nbviewer.ipython.org/urls/raw.github.com/qutip/qutip-notebooks/master/development/development-Qobj-extract-eliminate.ipynb)
 * [development-visualization-test](http://nbviewer.ipython.org/urls/raw.github.com/qutip/qutip-notebooks/master/development/development-visualization-test.ipynb)

### Master equation solver

 * [development-mesolve-and-liouvillians](http://nbviewer.ipython.org/urls/raw.github.com/qutip/qutip-notebooks/master/development/development-mesolve-and-liouvillians.ipynb)
 * [development-mesolve-expectation-values](http://nbviewer.ipython.org/urls/raw.github.com/qutip/qutip-notebooks/master/development/development-mesolve-expectation-values.ipynb)


### Stochastic solvers

 * [development-smesolve-tests](http://nbviewer.ipython.org/urls/raw.github.com/qutip/qutip-notebooks/master/development/development-smesolve-tests.ipynb)
 * [development-smesolve-inefficient-detection](http://nbviewer.ipython.org/urls/raw.github.com/qutip/qutip-notebooks/master/development/development-smesolve-inefficient-detection.ipynb)
 * [development-smesolve-heterodyne](http://nbviewer.ipython.org/urls/raw.github.com/qutip/qutip-notebooks/master/development/development-smesolve-heterodyne.ipynb)
 * [development-smesolve-milstein-speed-test](http://nbviewer.ipython.org/urls/raw.github.com/qutip/qutip-notebooks/master/development/development-smesolve-milstein-speed-test.ipynb)

## Benchmark notebooks

 * [development-benchmark-steadystate-1](http://nbviewer.ipython.org/urls/raw.github.com/qutip/qutip-notebooks/master/development/development-steadystate-solver-benchmarks-1.ipynb)
 * [development-benchmark-steadystate-2](http://nbviewer.ipython.org/urls/raw.github.com/qutip/qutip-notebooks/master/development/development-steadystate-solver-benchmarks-2.ipynb)



# Timeloop (with quantization)

## About

Timeloop is an infrastructure that aims to provide modeling, mapping and code-generation for Explicitly-Decoupled Data Orchestration (EDDO) architectures, with a focus on for dense- and sparse- tensor algebra workloads. It is built from two modular components:

* A fast analytical model that can emulate a range of EDDO architecture designs and provide performance and energy projections
* A mapper that that searches for an optimal mapping in the space of mappings of a tensor-algebra problem on a given architecture

## Fork additions

Additions to account for specifying different workload tensors bitwidths during the mapping evaluation.

## Documentation

Timeloop documentation is hosted at https://timeloop.csail.mit.edu/timeloop. The guides there cover installation, usage and examples.
For a deeper understanding of Timeloop's internals please read the original [ISPASS 2019 paper](https://parashar.org/ispass19.pdf).

## Tutorial

New users are strongly encouraged to complete the original Timeloop [tutorial](https://accelergy.mit.edu/tutorial.html). Serially walking through the [exercises](https://github.com/Accelergy-Project/timeloop-accelergy-exercises/) from the tutorial serves as an essential hands-on introduction to the tool.

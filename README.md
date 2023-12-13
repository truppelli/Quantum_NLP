# Quantum Natural Language Processing

The purpose of this repository is to showcase how natural language can be mapped into quantum states and Grover's search algorithm can be applied for query answering functionality.

## Installation

Create an Anaconda environment [Anaconda](https://www.anaconda.com/download) to manage your environments.

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install the following:

```bash
pip install numpy qiskit lambeq discopy jupyterlab
```

In order to import the development environment used in this repo, navigate to the python39.yaml file and execute:

```bash
conda env create -f python39.yaml
```

## Usage

The Quantum_NLP.ipynb script is used to convert natural language to quantum states by using Lambek typelogical grammars.

The Grovers_Search.ipynk script investigates the application of Grover's algorithm on queries.

## References

This work is built on top of the following projects:

[DisCoPy](https://discopy.org/)

[Lambeq](https://cqcl.github.io/lambeq/)

[Qiskit](https://www.ibm.com/quantum/qiskit)

[Quantum Decomp](https://github.com/fedimser/quantum_decomp)

## Contributing

Pull requests are welcome. To push changes, please open an issue and describe the feature you are developing. After review, a formal merge request can proceed forward.

## License

[Apache 2.0](https://www.apache.org/licenses/LICENSE-2.0)

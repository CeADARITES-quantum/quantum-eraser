# Summer Jam - University College Dublin 2020

# Quantum Eraser using Qiskit

The quantum eraser is an experiment normally executed in optics, where ideally single photons would pass through a double slit to form an interference pattern, a pattern that can be destroyed by performing a measurement at the slit and then recovered by the eraser. However, the most accessible implementation is built with a laser beam, which does not send single photons.

The aim of this project is to use qubits and the Single Qubit Gates present in Qiskit to reproduce a quantum eraser.

The quantum eraser is an experiment that invites to reflecting on the nature of entanglement. Its most straightforward interpretation would be that, thanks to quantum mechanics, the collapse produced by a measurement could be erased by the application of operators to an entangled element.

# QUANTUM ERASER EXPERIMENT

Determining the path of a photon after a passing a double slit would supress the interference pattern. Since this knowledge or measurement is achieved through an entangled photon, one could assumed that there is instant communication between detectors. The truth is that in experimental realizations, a good study of the data must be done in order to filter noise and determine the correct timing of events.

### Getting started

```
virtualenv venv --python=python3
source venv/bin/activate
```

#### Installing Qiskit

```
pip install qiskit
pip install qiskit[visualization]
```

#### jupyter notebook

```
pip install jupyter
jupyter notebook
```

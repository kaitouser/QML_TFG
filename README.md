<h1 align="center">
  QML_TFG
</h1>

<p align="center">
  <img src="https://img.shields.io/github/followers/kaitouser?style=flat-square&logo=github"/>
  <img src="https://img.shields.io/github/commit-activity/t/kaitouser/QML_TFG?style=flat-square&color=green"/>
  <img src="https://img.shields.io/pypi/l/qiskit?style=flat-square&color=orange"/>
</p>

# Description

Quantum embedding became an interesting topic inside the world of data compression and classification. 
This field tries to represent classical data via quantum features, using differents properties of quantum physics like superposition or entanglement.

The purpose of this project is to make an introduction into this new field, experiment with the different algorithms that are being studied in this field, and implement them using the available libraries.

# Installation

![Static Badge](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=Jupyter&logoColor=white&labelColor=black&link=https%3A%2F%2Fjupyter.org%2F)
![Static Badge](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=Python&logoColor=white&labelColor=black&link=https%3A%2F%2Fwww.python.org%2F)
![Static Badge](https://img.shields.io/badge/Qiskit-6929C4?style=for-the-badge&logo=Qiskit&labelColor=black&link=https%3A%2F%2Fdocs.quantum.ibm.com%2F)

First, we have to create a notebook using the Jupyter webapp we just installed.

Now, here are the command lines required to install the packages in our notebook:
~~~
!pip install requirements.txt
~~~

This tutorial isn't available for newer versions of Qiskit (>= v1.0).

# Content

During this [tutorial](https://github.com/kaitouser/QML_TFG/blob/d71f04b7f191ca446d577f28cbfe7871e80e2c48/Tutorial/Quantum%20encoding/Quantum_representations_tutorial.ipynb) there are different types of quantum algorithms explained, grouped by main types or patterns called representations:

 - Continous representation:
   - [QSMC_QSNC](https://www.researchgate.net/publication/257641707_Image_storage_retrieval_compression_and_segmentation_in_a_quantum_system)
   - [OQIM](https://doi.org/10.1007/s11128-019-2463-7)
 - Discrete representation:
    - [NEQR](https://doi.org/10.1007/s11128-013-0567-z)
    - [BRQI](https://ieeexplore.ieee.org/document/8470069)
    - [GQIR](https://doi.org/10.1007/s11128-015-1099-5)
 - Mixed representation:
    - [Qubit Lattice](https://doi.org/10.1117/12.485960)
    - [FRQI](https://doi.org/10.1007/s11128-010-0177-y)
    - [MCRQI](https://ieeexplore.ieee.org/document/6051718)
  
Part of the content included in this tutorial comes from Marina Lisnichenko work, which can be access in the [referenced GitHub](https://github.com/UralmashFox/QPI).

# Credits
In collaboration with Universitat Autònoma de Barcelona (UAB).

Proper credits to professor Fernando Vilariño and Quantum Physicist Matías Bilkis for helping to develop this project.

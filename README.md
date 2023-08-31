[![Python package](https://github.com/Jammyzx1/Carbon-capture-fingerprint-generation/actions/workflows/ccs_ci.yaml/badge.svg)](https://github.com/Jammyzx1/Carbon-capture-fingerprint-generation/actions/workflows/ccs_ci.yaml)

# Carbon-capture-fingerprint-generation
The code allows for the generation of a molecular representation for amines used in carbon capture, generation from molecular fragment combinations and analysis of the chemical space.
Documentation of the functionality can be found https://jammyzx1.github.io/Carbon-capture-fingerprint-generation/

Copyright IBM Corporation 2022.
SPDX-License-Identifier: MIT

This toolkit is a collection of tools designed to assist in the design and prediction
of carbon capture molecular properties. The current capabilities are:
1. Chemical space plotting and analysis
1. Chemical fingerprint generation
1. Molecular dataset analysis
1. Duplication of molecular string data identification

Please cite if you use the code:
```
@article{mcdonagh2022chemical,
  title={Chemical space analysis and property prediction for carbon capture amine molecules},
  author={McDonagh, James and Zavitsanou, Stamatia and Harrison, Alexander and Zubarev, Dimitry and Wunsch, Benjamin and van Kessel, Theordore and Cipcigan, Flaviu},
  year={2022},
  url={https://chemrxiv.org/engage/chemrxiv/article-details/62e110cbadb01e653cae19f4}
```

# Contributing
Please make contributions to the `dev` branch and open PRs to merge in to `master` branch.
We use docstring and unit tests to help maintain the library these are called through the `unit_test.py` script.
Please make sure all tests pass and add new tests for new code.

# Installation

Once you have installed Anaconda, run the following commands

```
git clone  $THIS_REPO

# careful, removes previous environment with the same name
yes | conda create --name ccsfp python=3.8
conda activate ccsfp
python setup.py install
python unit_test.py
```

The notebooks directory has examples which can be run to check the code runs correctly.

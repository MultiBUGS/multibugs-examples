# Code for MultiBUGS paper

This repository contains the models, data, inits and scripts required to replicate the results in

Goudie, R. J. B., Turner, R. M., De Angelis, D., Thomas, A. (2017) MultiBUGS: A parallel implementation of the BUGS modelling framework for faster Bayesian inference [arXiv:1704.03216](https://arxiv.org/abs/1704.03216)

## Seeds example

To run the `seeds` model script from the command line, edit the code as follows, and then run from the Windows CMD.

- Replace `C:/MultiBUGS/` with the path to the directory containing `MultiBUGS.exe`.
- Replace `C:/multibugs-examples/` with the path to the directory containing this file.
- Also replace `C:/multibugs-examples/` with the path to the directory containing this file on line 2 of `seeds_script.txt`

```
cd C:/MultiBUGS/
MultiBUGS.exe /PAR C:/multibugs-examples/seeds_script.txt
```

## E-health example

To run the `e-health` model script from the command line, edit the code as follows, and then run from the Windows CMD.

- Replace `C:/MultiBUGS/` with the path to the directory containing `MultiBUGS.exe`.
- Replace `C:/multibugs-examples/` with the path to the directory containing this file.
- Also replace `C:/multibugs-examples/` with the path to the directory containing this file on line 2 of `ehealth_script.txt`

```
cd C:/MultiBUGS/
MultiBUGS.exe /PAR C:/multibugs-examples/ehealth_script.txt
```

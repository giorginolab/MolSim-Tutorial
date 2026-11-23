# MolSim-Tutorial
Material for the Molecular Simulations module (for Prof. Fuxreiter)

Toni Giorgino

## How to run

The code contained in this repo is structure in large part as IPython notebooks. They can be run in three ways:

* On your local machine. That's probably the easiest and most didactic for interpreting the intermediate files.
* On [Google Colab](https://colab.research.google.com/drive/1Fki7NjHlhYYqGWHdGakUJuu0TP40YdIC#scrollTo=sEPay7j6oqf-). Just open Colab and point it to the file's URL. Simulations run much faster if you request a GPU runtime.
* On Binder. Somewhat slow but comes with a pre-installed environment. [Open in binder](https://mybinder.org/v2/gh/giorginolab/MD-Tutorial-Data/binderenv?urlpath=git-pull%3Frepo%3Dhttps%253A%252F%252Fgithub.com%252Fgiorginolab%252FMolSim-Tutorial%26urlpath%3Dlab%252Ftree%252FMolSim-Tutorial%252F%26branch%3Dmain)

## Day 2

Here are the links:

* Analysis with MDTraj: https://github.com/giorginolab/MD-Tutorial-Data/blob/main/notebooks/2_MDTraj_analysis.ipynb . If "open in Colab" does not work automatically, manually open Colab and point it to said address.
* Docking: https://github.com/giorginolab/MolSim-Tutorial/blob/main/docking/Docking_2024.ipynb or [here](https://colab.research.google.com/drive/1J0at4RhO00BUUI1r1MR6N5sfZdLPZLgj) . Same as above.

Remember that we use condacolab, so there will be an initial restart of the kernel.


## Editions

This repository (`main`) holds the latest edition (2024). Earlier material from the same course (Prof. Fuxreiter, University of Padova) is kept, with full history, under tags:

| Tag | Content | Former repository |
|---|---|---|
| [`2022-MDTraj-UniPD`](../../tree/2022-MDTraj-UniPD) | MDTraj trajectory analysis, PLUMED | `2022-MD-Trajectory-Tutorial-UniPD` |
| [`2023-OpenMM-UniPD`](../../tree/2023-OpenMM-UniPD) | OpenMM class | `2023-OpenMM-Tutorial-UniPD` |
| [`2023-OpenMM-MD-UniPD`](../../tree/2023-OpenMM-MD-UniPD) | OpenMM and MD analysis slides | `2023-OpenMM-MD-UniPD` |
| [`2024-MolSim-UniPD`](../../tree/2024-MolSim-UniPD) | Molecular Simulations module (same as `main`, before this table and link fixes) | `2024-MolSim-UniPD` |

To get an edition: `git checkout 2023-OpenMM-UniPD`. Each tag is the final state of the original repository, which has since been merged here (full history preserved).

Related: Markov state model classes for this course are in [Markov-Tutorial](https://github.com/giorginolab/Markov-Tutorial); shared data in [MD-Tutorial-Data](https://github.com/giorginolab/MD-Tutorial-Data).

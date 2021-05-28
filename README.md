# rna-folding

Implementation of the Zuker algorithm for the RNA folding problem.

![Origami](/aes/origami.jpg)

## 📗 Introduction

RNA folding is the process by which a linear ribonucleic acid (RNA) molecule acquires secondary structure through intra-molecular interactions. The folded domains of RNA molecules are often the sites of specific interactions with proteins in forming RNA–protein (ribonucleoprotein) complexes.

## 🔑 Prerequisites

Please make sure that you have **Python 3.8.3** or greater installed on your machine. It is also possible that the code will run for previous versions (not tested).

Also make sure that the following libraries are installed and up-to-date:
* numpy
* matplotlib
* importlib

In addition, the **draw_rna** visualization tool was utilized. **draw_rna** was developed the Das Lab and can be found [here](https://github.com/DasLab/draw_rna). A tweaked version of its `draw.py` script is utilized in the frame of this implementation -included in the [src](/src) directory- as well as the `draw_struct` function which is proposed by **draw_rna** for RNA secondary structure visualization.

## 👟 Walkthrough

The [Jupyter notebook](/src/Zuker.ipynb) is fairly easy to run; it includes the implementation of the Zuker algorithm as well as the assumptions made in the toy problem.


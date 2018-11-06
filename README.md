**[summary](#Summary) | [contents](#Contents) | [usage](#Usage) | [running the notebooks](#Running-the-notebooks) | [citation](#Citation) | [issues](#Issues) |  [license](#License)**

# An inversion approach for subsurface injections

[![Build Status](https://travis-ci.org/simpeg-research/heagy-2018-injection-inversions.svg?branch=master)](https://travis-ci.org/simpeg-research/heagy-2018-injection-inversions)
[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/simpeg-research/heagy-2018-injection-inversions/master)
[![Azure](https://notebooks.azure.com/launch.png)](https://notebooks.azure.com/import/gh/simpeg-research/heagy-2018-injection-inversions)
[![License](https://img.shields.io/github/license/simpeg-research/heagy-2018-injection-inversions.svg)](https://github.com/simpeg-research/heagy-2018-injection-inversions/blob/master/LICENSE)
[![SimPEG](https://img.shields.io/badge/powered%20by-SimPEG-blue.svg)](http://simpeg.xyz)

## Summary

This repository contains the notebooks used to generate the examples shown in Chapter 6
of the thesis ["Electromagnetic methods for imaging subsurface injections"](https://github.com/lheagy/phd-thesis) by [Lindsey J. Heagy](https://github.com/lheagy). 

In this chapter, I discuss inversion strategies for imaging subsurface injections with hydraulic fracturing being the application of focus. I consider a DC resistivity experiment where the positive electrode is positioned within a steel-cased borehole and a return electrode is on the surface. I then consider several inversion approaches including a Tikhonov-style inversion and a parametric inversion. I then suggest an approach using effective medium theory to include a-priori information about the injected volume of proppant and fluid. 

<img src="figures/dc_parametric_inversion_phi_correctz0_large_r.png" width=80% align="middle">

## Contents

- [notebooks](notebooks):
    - [DC_2D_inversion_halfspace](/notebooks/DC_2D_inversion_halfspace.ipynb): 
    - [parametric_mappings](parametric_mappings.ipynb)

## Usage

### Online
The notebooks can be run online through [mybinder](https://mybinder.org/v2/gh/simpeg-research/heagy-2018-em-casing/master) or [azure notebooks](https://notebooks.azure.com/import/gh/simpeg-research/heagy-2018-em-casing).

### Locally
To run them locally, you will need to have python installed, preferably through [anaconda](https://www.anaconda.com/download/).

You can then clone this reposiroty. From a command line, run

```
git clone https://github.com/simpeg-research/heagy-2018-injection-inversions.git
```

Then `cd` into the `heagy-2018-injection-inversions`

```
cd heagy-2018-em-casing
```

To setup your software environment, we recommend you use the provided conda environment

```
conda env create -f environment.yml
source activate injection-inversions-environment
```

alternatively, you can install dependencies through pypi
```
pip install -r requirements.txt
```

You can then launch Jupyter
```
jupyter notebook
```

Jupyter will then launch in your web-browser.

## Running the notebooks

Each cell of code can be run with `shift + enter` or you can run the entire notebook by selecting `cell`, `Run All` in the toolbar.

<img src="https://raw.githubusercontent.com/simpeg-research/heagy-2018-emcyl/master/figures/cell_run_all.png" width=80% align="middle">

For more information on running Jupyter notebooks, see the [Jupyter Documentation](https://jupyter.readthedocs.io/en/latest/)

## Citation

coming soon...

## Issues

If you run into problems or bugs, please let us know by [creating an issue](https://github.com/simpeg-research/heagy-2018-injection-inversions/issues/new) in this repository.

## License

These notebooks are licensed under the [MIT License](/LICENSE) which allows academic and commercial re-use and adaptation of this work.

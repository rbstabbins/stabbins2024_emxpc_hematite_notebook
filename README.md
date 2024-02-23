# The Spectral Parameters Toolkit (sptk): Notebook for "­­Optimising ExoMars PanCam Multispectral Science II: Choosing and Using Multispectral Filters for Dynamic Planetary Surface Exploration with Linear Discriminant Analysis"

<p align="center">
  <a href="" rel="noopener">
 <img max-width=960px src="https://github.com/rbstabbins/stabbins2024_emxpc_hematite_notebook/blob/main/notebook_title.gif?raw=true" alt="Project logo"></a>
</p>

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.10697557.svg)](https://doi.org/10.5281/zenodo.10697557)

## Table of Contents

- [About](#about)
- [Setup](#setup)
- [Dataset](#dataset)
- [Data Products](#data-products)
- [Authors](#authors)
- [Acknowledgements](#acknowledgements)

## About <a name = "about"></a>

This notebook accompanies the paper 'Optimising ExoMars PanCam Multispectral Science II: Choosing and Using Multispectral Filters for Dynamic Planetary Surface Exploration with Linear Discriminant Analysis'.

The notebook demonstrates how to use the Spectral Parameters Toolkit (sptk) Python package to reproduce the results, data products and figures of the paper. 

Version 0.1 of **sptk**, used for this analysis, has been archived at: [doi:10.5281/zenodo.10692531](https://zenodo.org/doi/10.5281/zenodo.10692531).

The dataset required by this notebook has been archived at: [doi:10.5281/zenodo.10684347](https://zenodo.org/doi/10.5281/zenodo.10684347).

A copy of the data products and figures of the analysis, as used in the paper, has been archived at: [doi:10.5281/zenodo.10696385](https://zenodo.org/doi/10.5281/zenodo.10696385).

## Setup <a name = "setup"></a>

We recommend using conda to setup an environment for running this notebook.

You can install the recommended dependencies by creating your environment from the [```environment.yml```](./environment.yml) file:

```
conda env create -f environment.yml
```

Once the dependencies, including version 0.1 of **sptk** have completed installing, activate the environment with:

```
conda activate stabbins2024_exmpc_hematite_notebook
```

Alternatively, if you wish to use another environment manager, the dependencies for the notebook are:

```
ipykernel
pip
python == 3.10.8
sptk==0.1
```

## Dataset <a name = "dataset"></a>

The notebook requires access to the accompanying dataset for the study, that has been archived at: [doi:10.5281/zenodo.10684347](https://zenodo.org/doi/10.5281/zenodo.10684347).

Before running the notebook, download this repository and place the instrument file (```exm_pc_geol.csv```) in the [./data/instruments](./data/instruments) directory, and place the spectral library (```stabbins_exmpc_hematite_spectral_library/```) in the [./data/spectral_library](./data/spectral_library) directory.

## Data Products <a name = "data-products"></a>

Data products produced by this notebook will be exported to the ```./projects/stabbins2024_exmpc_hematite_paper_data_products/``` directory, that will be generated during execution.

A copy of the data products that will be produced have been archived at: [doi:10.5281/zenodo.10696385](https://zenodo.org/doi/10.5281/zenodo.10696385). These are the data products that were used for the accompanying paper.

To compare the results of the notebook with the archived dataset by linking inside the notebook, we recommend that you download this repository, unzip it, and place it in the ```./projects``` directory.

## Authors <a name = "authors"></a>

This notebook was designed and developed by [@rbstabbins](https://github.com/rbstabbins).

See also the list of [contributors](https://github.com/rbstabbins/sptk/contributors) who participated in this project.

## Acknowledgements <a name = "acknowledgements"></a>

Please see the dataset repository ([doi:10.5281/zenodo.10684347](https://zenodo.org/doi/10.5281/zenodo.10684347)) for acknowledgements and citation of the source datasets used in this study.

This project has been funded by the following grants:
- UK Space Agency Aurora Science Programme: Geochemistry to Geology for ExoMars 2020 visible to near infrared spectral variability ST/T001747/1
- UK Space Agency Mars Exploration Science Standard Call 2023: Exploring the Limits of Material Discrimination with CaSSIS Multiband Imaging ST/Y005910/1
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/bioexcel/biobb_wf_md_setup_api/master?filepath=biobb_wf_md_setup_api%2Fnotebooks%2Fbiobb_MDsetupAPI_tutorial.ipynb)

# Protein MD Setup tutorial using BioExcel Building Blocks (biobb) through REST API

**Based on the official [GROMACS tutorial](http://www.mdtutorials.com/gmx/lysozyme/index.html).**

***

This tutorial aims to illustrate the process of **setting up a simulation** system containing a **protein**, step by step, using the **BioExcel Building Blocks library (biobb)**. The particular example used is the **Lysozyme** protein (PDB code 1AKI).

***

## Settings

### Auxiliar libraries used

* [nb_conda_kernels](https://github.com/Anaconda-Platform/nb_conda_kernels): Enables a Jupyter Notebook or JupyterLab application in one conda environment to access kernels for Python, R, and other languages found in other environments.
* [nglview](http://nglviewer.org/#nglview): Jupyter/IPython widget to interactively view molecular structures and trajectories in notebooks.
* [ipywidgets](https://github.com/jupyter-widgets/ipywidgets): Interactive HTML widgets for Jupyter notebooks and the IPython kernel.
* [plotly](https://plot.ly/python/offline/): Python interactive graphing library integrated in Jupyter notebooks.
* [simpletraj](https://github.com/arose/simpletraj): Lightweight coordinate-only trajectory reader based on code from GROMACS, MDAnalysis and VMD.

### Conda Installation and Launch

```console
git clone https://github.com/bioexcel/biobb_wf_md_setup_api.git
cd biobb_wf_md_setup_api
conda env create -f conda_env/environment.yml
conda activate biobb_MDsetupAPI_tutorial
jupyter-nbextension enable --py --user widgetsnbextension
jupyter-nbextension enable --py --user nglview
jupyter-notebook biobb_wf_md_setup_api/notebooks/biobb_MDsetupAPI_tutorial.ipynb
```

***

## Tutorial

Click here to [view tutorial in Read the Docs]()

Click here to [execute tutorial in Binder](https://mybinder.org/v2/gh/bioexcel/biobb_wf_md_setup_api/master?filepath=biobb_wf_md_setup_api%2Fnotebooks%2Fbiobb_MDsetupAPI_tutorial.ipynb)

***

## Version
January 2020 Release

## Copyright & Licensing
This software has been developed in the [MMB group](http://mmb.irbbarcelona.org) at the [BSC](http://www.bsc.es/) & [IRB](https://www.irbbarcelona.org/) for the [European BioExcel](http://bioexcel.eu/), funded by the European Commission (EU H2020 [823830](http://cordis.europa.eu/projects/823830), EU H2020 [675728](http://cordis.europa.eu/projects/675728)).

* (c) 2015-2020 [Barcelona Supercomputing Center](https://www.bsc.es/)
* (c) 2015-2020 [Institute for Research in Biomedicine](https://www.irbbarcelona.org/)

Licensed under the
[Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0), see the file LICENSE for details.

![](https://bioexcel.eu/wp-content/uploads/2019/04/Bioexcell_logo_1080px_transp.png "Bioexcel")

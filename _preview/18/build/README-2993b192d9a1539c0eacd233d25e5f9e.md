<img src="MHW_logo.png" alt="MHW_thumbnail" width="300"/>

# Marine Heatwaves Cookbook

[![nightly-build](https://github.com/ProjectPythia/marine-heatwave-cookbook/actions/workflows/nightly-build.yaml/badge.svg)](https://github.com/ProjectPythia/marine-heatwave-cookbook/actions/workflows/nightly-build.yaml)
[![Binder](https://binder.projectpythia.org/badge_logo.svg)](https://binder.projectpythia.org/v2/gh/ProjectPythia/marine-heatwave-cookbook/main?labpath=notebooks)
[![DOI](https://zenodo.org/badge/656355237.svg)](https://zenodo.org/badge/latestdoi/656355237)

This main goal of this Marine Heatwaves Cookbook is to show how to detect and forecast marine heatwaves based on available observational and model forecast data.
The step and code used in the cookbook is also used to generate the [Marine Heatwave Portal at NOAA Physcial Science Laboratory](https://psl.noaa.gov/marine-heatwaves/)
To understand more scientific detail of the forecast skill please check out [Jacox et al., 2022](http://doi.org/10.1038/s41586-022-04573-9)

This cookbook is initiated during the pythia cookoff 2023.

## Motivation

The marine heatwave have started to become one of the many "hot topics" in climate science.
This cookbook is aiming to show how a marine heatwave is detected and forecast based on [Jacox et al., 2022](http://doi.org/10.1038/s41586-022-04573-9)

## Authors

[Chia-Wei Hsu](https://github.com/chiaweh2)

### Contributors

<a href="https://github.com/chiaweh2/marine-heatwave-cookbook/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=chiaweh2/marine-heatwave-cookbook" />
</a>

## Structure

This cookbook is broken up into two main chapters - "Foundation" and "Application"

### Foundation

In this chapter, we will show how a marine heatwave is detected over the ocean using observational data.
We will also explain one of the hot discussion topics in the marine heatwave field - "[Marine heatwaves need clear definitions so coastal communities can adapt](https://www.nature.com/articles/d41586-023-00924-2)"

### Application

In the application chapter, we will show

1. How a marine heatwave is being forecast shown in [PSL Marine Heatwave Portal](https://psl.noaa.gov/marine-heatwaves/)?
1. Is it possible to track how a marine heatwave moves in the ocean?

## Running the Notebooks

You can either run the notebook using [Binder](https://binder.projectpythia.org/) or on your local machine.

### Running on Binder

The simplest way to interact with a Jupyter Notebook is through
[Binder](https://binder.projectpythia.org/), which enables the execution of a
[Jupyter Book](https://jupyterbook.org) in the cloud. The details of how this works are not
important for now. All you need to know is how to launch a Pythia
Cookbooks chapter via Binder. Simply navigate your mouse to
the top right corner of the book chapter you are viewing and click
on the rocket ship icon, (see figure below), and be sure to select
“launch Binder”. After a moment you should be presented with a
notebook that you can interact with. I.e. you’ll be able to execute
and even change the example programs. You’ll see that the code cells
have no output at first, until you execute them by pressing
{kbd}`Shift`\+{kbd}`Enter`. Complete details on how to interact with
a live Jupyter notebook are described in [Getting Started with
Jupyter](https://foundations.projectpythia.org/foundations/getting-started-jupyter.html).

### Running on Your Own Machine

If you are interested in running this material locally on your computer, you will need to follow this workflow:

(Replace "cookbook-example" with the title of your cookbooks)

1. Clone the `https://github.com/chiaweh2/marine-heatwave-cookbook` repository:

   ```bash
    git clone https://github.com/chiaweh2/marine-heatwave-cookbook.git
   ```

1. Move into the `marine-heatwave-cookbook` directory
   ```bash
   cd marine-heatwave-cookbook
   ```
1. Create and activate your conda environment from the `environment.yml` file
   ```bash
   conda env create -f environment.yml
   conda activate cookbook-example
   ```
1. Move into the `notebooks` directory and start up Jupyterlab
   ```bash
   cd notebooks/
   jupyter lab
   ```

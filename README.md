<img src="https://crocus-urban.org/wp-content/uploads/sites/115/2023/03/CROCUS-Logo_preview_R2.png" alt="thumbnail" width="300"/>

# Air Quality Sensors Cookbook

[![nightly-build](https://github.com/EVS-ATMOS/air-quality-sensors/actions/workflows/nightly-build.yaml/badge.svg)](https://github.com/EVS-ATMOS/air-quality-sensors/actions/workflows/nightly-build.yaml)
[![Binder](http://binder.mypythia.org/badge_logo.svg)](http://binder.mypythia.org/v2/gh/ProjectPythia/cookbook-template/main?labpath=notebooks)

This Air Quality Sensor Cookbook covers working with air quality instrumentation at the Argonne Testbed for Multiscale Observational Science (ATMOS). 

## Motivation
CROCUS will deploy a wide array of air quality instrumentation throughout Chicago. To do this, testing of these instruments against known standards are needed to understand how they perform across many environmental factors. 

## Authors

[Joe O'Brien](@jrobrien91), [Second Author](@second-author), etc. _Acknowledge primary content authors here_

### Contributors

<a href="https://github.com/EVS-ATMOS/air-quality-sensors/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=EVS-ATMOS/air-quality-sensors" />
</a>

## Structure

(State one or more sections that will comprise the notebook. E.g., _This cookbook is broken up into two main sections - "Foundations" and "Example Workflows."_ Then, describe each section below.)

### Section 1 ( Replace with the title of this section, e.g. "Foundations" )

(Add content for this section, e.g., "The foundational content includes ... ")

### Section 2 ( Replace with the title of this section, e.g. "Example workflows" )

(Add content for this section, e.g., "Example workflows include ... ")

## Running the Notebooks

You can either run the notebook using [Binder](https://mybinder.org/) or on your local machine.

### Running on Binder

The simplest way to interact with a Jupyter Notebook is through
[Binder](https://mybinder.org/), which enables the execution of a
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

1. Clone the `https://github.com/EVS-ATMOS/air-quality-sensors` repository:

   ```bash
    git clone https://github.com/EVS-ATMOS/air-quality-sensors.git
   ```

1. Move into the `cookbook-example` directory
   ```bash
   cd cookbook-example
   ```
1. Create and activate your conda environment from the `environment.yml` file
   ```bash
   conda env create -f environment.yml
   conda activate air-quality-sensors-dev
   ```
1. Move into the `notebooks` directory and start up Jupyterlab
   ```bash
   cd notebooks/
   jupyter lab
   ```

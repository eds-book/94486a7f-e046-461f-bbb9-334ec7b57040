<div align="center">
    <h6>Environmental Data Science Book</h6>
</div>

<p align="center">
<img src="https://github.com/alan-turing-institute/environmental-ds-book/blob/master/book/figures/logo/logo.png?raw=True" alt="thumbnail" width="200"/>
</p>

<div align="center">
    <h1>Tree crown delineation using detectreeRGB</h1>
</div>

<p align="center">
    <a href="https://github.com/eds-book-gallery/94486a7f-e046-461f-bbb9-334ec7b57040/blob/main/LICENSE">
        <img alt="license" src="https://img.shields.io/badge/license-MIT-yellow.svg">
    </a>
    <a href="https://notebooks.gesis.org/binder/v2/gh/eds-book-gallery/94486a7f-e046-461f-bbb9-334ec7b57040/main?labpath=notebook.ipynb">
        <img alt="binder" src="https://mybinder.org/badge_logo.svg">
    </a>
    <a href="https://github.com/eds-book-gallery/94486a7f-e046-461f-bbb9-334ec7b57040/actions/workflows/render.yaml">
        <img alt="render" src="https://github.com/eds-book-gallery/94486a7f-e046-461f-bbb9-334ec7b57040/actions/workflows/render.yaml/badge.svg">
    </a>
    <a href="https://github.com/alan-turing-institute/environmental-ds-book/pull/4">
        <img alt="review" src="https://img.shields.io/badge/view-review-purple">
    </a>
    <br/>
</p>

<p align="center">
    <a href="https://w3id.org/ro-id/94486a7f-e046-461f-bbb9-334ec7b57040">
        <img alt="RoHub" src="https://img.shields.io/badge/RoHub-FAIR_Executable_Research_Object-2ea44f?logo=Open+Access&logoColor=blue">
    </a>
    <a href="https://doi.org/10.24424/2h9y-jn41">
        <img alt="doi" src="https://zenodo.org/badge/DOI/10.24424/2h9y-jn41.svg">
    </a>
</p>

<p align="center">
<img src="https://user-images.githubusercontent.com/13321552/222992138-d1665903-856f-4506-a3e0-37b7f04e4fe2.png?raw=True" alt="thumbnail" width="300"/>
</p>

# How to run

## Running on Binder
The notebook is designed to be launched from Binder. 

Click the **Launch Binder** button at the top level of the repository

## Running locally
You may also download the notebook from GitHub to run it locally:
1. Open your terminal

2. Check your conda install with `conda --version`. If you don't have conda, install it by following these instructions (see [here](https://docs.conda.io/en/latest/miniconda.html))

3. Clone the repository
    ```bash
    git clone https://github.com/eds-book-gallery/94486a7f-e046-461f-bbb9-334ec7b57040.git
    ```

4. Move into the cloned repository
    ```bash
    cd 94486a7f-e046-461f-bbb9-334ec7b57040
    ```

5. Create and activate your environment from the `.binder/environment.yml` file
    ```bash
    conda env create -f .binder/environment.yml
    conda activate 94486a7f-e046-461f-bbb9-334ec7b57040
    ```  

6. Launch the jupyter interface of your preference, notebook, `jupyter notebook` or lab `jupyter lab`

# Credits
The **How to run** section was adapted from the [Project Pythia Cookbook](https://cookbooks.projectpythia.org/) project.
The workflow actions were adapted from [2i2c’s hub-user-image-template](https://github.com/2i2c-org/hub-user-image-template) released under BSD-3-Clause license.
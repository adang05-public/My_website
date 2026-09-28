# Overview

Welcome to my quarto website! It currently contains 2 blog posts about penguins from the palmerpenguins dataset, and a blog post about my first week at MDS. Enjoy!

# Build Instructions

## Pre-requisites for building:

### Required:
1. uv package manager
2. R installation
3. python installation (can be installed via uv)
4. quarto installation
5. Jupyter Notebooks installation

### Recommended:
1. RStudion installation
2. VSCode / Positron installation
3. RTools installation

## To clone with HTTPS:

1. run ```git clone https://github.com/adang05-public/My_website.git``` in the folder you want to clone the repository in
2. run ``` uv sync``` in the main repo folder to download libraries for Python
3. run ```R``` in the main repo folder
4. run ```renv::restore()``` to download libraries for R, and ```q()``` to leave the R terminal
5. run ```uv run quarto preview``` or ```uv run quarto render``` to preview or render the website respectively
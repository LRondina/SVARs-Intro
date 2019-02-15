# Introduction to Structural VAR models

This short class is designed for M.Sc. Economics students as a part of the Research Methods module.

The aim of the class is to introduce the students to Vector Autoregression (VAR) and Structural Vector Autoregression (SVAR) models.

The focus is on the basic concepts and practical implementation of SVARs. As such, important aspects like the estimation of these models or more advanced identification techniques are not covered.

### Contents

`Slides.pdf`: Trends and cycles, Introduction to VAR and SVAR models, Recursive (short-run) restriction, Example.

`SVAR_demo.mlx`: MATLAB implementation of the example in the slides. This is an interactive Live Script with extensive comments and explanations. Open this file inside MATLAB or see the HTML or PDF version for a quick preview.

`SVAR_demo.html`: HTML version of `SVAR_demo.mlx`. For a rendered version see [here](https://lrondina.github.io/matlab_html_scripts/SVAR_demo.html) or [here](http://htmlpreview.github.io/?https://github.com/LRondina/SVARs-Intro/blob/master/Codes/SVAR_demo.html).

`SVAR_demo.pdf`: PDF version of `SVAR_demo.mlx`.

`SVAR_demo.m`: Less exciting version of `SVAR_demo.mlx`.

### Download

This repository contains a **git submodule** with the VAR toolbox. If you try to simply clone the repository or download it as a zip file, GitHub will download the files of this repository **without** the files in `Codes/VAR_toolbox`.

To obtain this repository with the toolbox included, you have two options:

1. Direct download ([zip version](https://lrondina.github.io/downloads/SVARs-Intro.zip))

2. Clone with submodule: `git clone --recurse-submodules https://github.com/LRondina/SVARs-Intro`

### Software and dependencies

- A recent version of MATLAB (R2018b or never) is required for the Live Script `SVAR_demo.mlx`.

- [VAR Toolbox 2.0](https://sites.google.com/site/ambropo/MatlabCodes) (a version of this toolbox is provided with this repository with minor modifications to handle plots and figures)

- [Datafeed toolbox](https://uk.mathworks.com/products/datafeed.html)




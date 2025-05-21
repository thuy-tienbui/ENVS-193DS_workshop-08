# ENVS 193DS, Workshop 8

Spring 2025

## General information

This dataset is from: Valliere, Justin; Zhang, Jacqueline; Sharifi, M.; Rundel, Philip (2019). Data from: Can we condition native plants to increase drought tolerance and improve restoration success? [Dataset]. Dryad. [https://doi.org/10.5061/dryad.v0861f7](https://doi.org/10.5061/dryad.v0861f7)  

The published paper is: Valliere J. M., J. Zhang, M. R. Sharifi, and P. W. Rundel. 2019. Can we condition native plants to increase drought tolerance and improve restoration success? Ecological Applications 29(3):e01863. [10.1002/eap.1863](https://doi.org/10.1002/eap.1863).

This repository is for demonstrating fitting models with categorical and continuous predictors and model selection.

### Packages

Make sure you have these installed before workshop!

```
library(tidyverse) # general use
library(here) # file organization
library(janitor) # cleaning data frames
library(readxl) # reading excel files
library(scales) # modifying axis labels
library(ggeffects) # getting model predictions
library(MuMIn) # model selection
```

## Data and file information

File structure:

```
.
├── ENVS-193DS_workshop-08.Rproj
├── README.md
├── code                                     # code folder
│   ├── workshop-08_code_KEY.Rmd             # keys
│   ├── workshop-08_code_KEY.html            # rendered output is from .qmd key
│   ├── workshop-08_code_KEY.qmd
│   ├── workshop-08_code_KEY_files
│   ├── workshop-08_code_TEMPLATE.Rmd        # templates
│   └── workshop-08_code_TEMPLATE.qmd
└── data                                     # data folder
    └── Valliere_etal_EcoApps_Data.xlsx
```

All code is in the `code` folder. The code runs models, generates model predictions, and visualizes data.

## Rendered output

The rendered key is [here](https://an-bui.github.io/ENVS-193DS_workshop-08/code/workshop-08_code_KEY.html).  

You will need to find your own rendered output! Insert a link here.

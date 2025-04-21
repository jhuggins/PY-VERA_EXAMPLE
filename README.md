
## 1. Tutorial

This tutorial shows you how to build and run a simple linear regression model to forecast water temperature for the VERA Forecasting Challenge. You’ll integrate R‑developed tools to preprocess the required data, with validation and submission steps implemented in a Python notebook.

## 2. Setting up your Colab Environment


You can run these commands in your colab notebook for required R packages installation (Setup):

```!R -e "install.packages(c('reticulate','dplyr','arrow'), repos='http://cran.us.r-project.org')" ``` 

```!R -e "remotes::install_github('LTREB-reservoirsvera4castHelpers')" ``` 

## 3. Get the code

**1. Open Directly in Colab (Recommended)**  
Just click the “Open in Colab” badge at the top of the `Vera_Example.ipynb` notebook, and it will open the notebook directly in your Colab environment (login to your Google account if required).  
Run the “Setup” commands above to install all required R libraries.

**2. Open from GitHub inside Colab**
Go to https://colab.google/ →  Select open colab → Select GitHub → paste "https://github.com/rohitshukla01/PY-VERA_EXAMPLE/blob/main/Vera_Example.ipynb" → press Enter.
Run the “Setup” commands to install R Libraries

**3. Download ZIP & Upload Manually**
On GitHub, click Code → Download ZIP Unzip anywhere on your computer open Google Colab, go to File → Upload notebook (Vera_Example.ipynb).
Run the “Setup” commands to install R Libraries

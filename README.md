
## 📘 1. Tutorial

This tutorial shows you how to build and run a simple linear regression model to forecast water temperature for the VERA Forecasting Challenge. You’ll integrate R‑developed tools to preprocess the required data, with validation and submission steps implemented in a Python notebook.

## ⚙️ 2. Setting up your Colab Environment with R packages


You can run these commands in your colab notebook for required R packages installation (Setup):

```!R -e "install.packages(c('reticulate','dplyr','arrow'), repos='http://cran.us.r-project.org')" ``` 

```!R -e "remotes::install_github('LTREB-reservoirsvera4castHelpers')" ``` 

## 🚀3. Get the code

**✅ 1. Open Directly in Colab (Recommended)**  
Just click the “Open in Colab” badge at the top of the `Vera_Example.ipynb` notebook, and it will open the notebook directly in your Colab environment (login to your Google account if required).  
Run the “Setup” commands above to install all required R libraries.

**🔗 2. Open from GitHub inside Colab**  
Go to [https://colab.research.google.com](https://colab.research.google.com) → Select **"Open notebook"** → Choose the **GitHub** tab → Paste  
`https://github.com/rohitshukla01/PY-VERA_EXAMPLE/blob/main/Vera_Example.ipynb`  
→ Press **Enter** and select the notebook.  
Run the “Setup” commands to install all required R libraries.

**📦 3. Download ZIP & Upload Manually**  
On GitHub, click **Code → Download ZIP**.  
Unzip the folder anywhere on your computer.  
Open [Google Colab](https://colab.research.google.com), go to **File → Upload notebook**, and select `Vera_Example.ipynb`.  
Run the “Setup” commands to install all required R libraries.

## ⬆️ 4. Upload your Notebook Directly to GitHub from Colab 
If you’ve made changes in the notebook and want to save them to your GitHub:

1. In Google Colab, click on **File → Save a copy in GitHub**  
2. In the dialog box:  
   - **Repository:** `your-username/Your_Repo_name`  
   - **File path:** `Your_Forecasting_code_name.ipynb`  
   - Add a short **commit message**, e.g., `Vera Forecast Challenge Example`  
3. Click **OK** to push the notebook directly to your GitHub repo.

> 💡 Make sure you’re logged into your GitHub account in your browser when using this feature.




## 📘 1. Tutorial

This tutorial shows you how to build and run a simple linear regression model to forecast water temperature for the VERA Forecasting Challenge. You’ll integrate R‑developed tools to preprocess the required data, with validation and submission steps implemented in a Python notebook.

## 🚀2. Get the code

**✅ Option 1. Fork and open from GitHub inside Colab (Recommended)** 
- Sign into GitHub and navigate to the tutorial repository [https://github.com/LTREB-reservoirs/PY-VERA_EXAMPLE](https://github.com/LTREB-reservoirs/PY-VERA_EXAMPLE).
- Click the "Fork" button on the top right of the repository page to fork a copy of the repository to your own GitHub account.
- Once your fork is created, **in a new browser tab**, go to [https://colab.research.google.com](https://colab.research.google.com). You may need to log into your Google account to set up Colab if you have never used it before.
-  Select **"open notebook"** → Choose the **GitHub** tab
- Go back to your forked GitHub repository and copy the link to the repository. It will be something like: `https://github.com/YourUsername/PY-VERA_EXAMPLE/blob/main/Vera_Example.ipynb`. Paste this link in the **GitHub** tab search bar → Press **Enter**. 
- From your account, select the `PY-VERA_EXAMPLE` repository and `main` branch to open in Colab. Click on the `Vera_Example.ipynb` file to open.
- You have now opened your own copy of the `Vera_Example.ipynb` tutorial in Colab.
- Run the “Setup” commands below to install all required R libraries.
- Any changes you make and save will be committed directly to your fork on GitHub. When you save for the first time, you may need to verify your account and permit Colab to access your GitHub account to make the first commit.
- Once you have made your first commit on your forked repository, an "Open in Colab" badge will automatically be generated at the top of the `Vera_Example.ipynb` file. From now on, you can simply click this button to open the file in your Colab.

**🔗 Option 2. Open directly in Colab from the LTREB-reservoirs organization**  
- Just click the “Open in Colab” badge at the top of the `Vera_Example.ipynb` notebook, and it will open the notebook directly in your Colab environment (login to your Google account if required).  
- Run the “Setup” commands below to install all required R libraries.
- If you make changes to the code and now wish to save them to your GitHub:
  1. In Google Colab, click on **File → Save a copy in GitHub**  
  2. In the dialog box:  
     - **Repository:** `your-username/Your_Repo_name`  
     - **File path:** `Your_Forecasting_code_name.ipynb`  
     - Add a short **commit message**, e.g., `Vera Forecast Challenge Example`  
  3. Click **OK** to push the notebook directly to your GitHub repo.

> 💡 Make sure you’re logged into your GitHub account in your browser when using this feature.

**📦 Option 3. Download ZIP & Upload Manually**  
- On GitHub, click **Code → Download ZIP**.  
- Unzip the folder anywhere on your computer.  
- Open [Google Colab](https://colab.research.google.com), go to **File → Upload notebook**, and select `Vera_Example.ipynb`.  
- Run the “Setup” commands below to install all required R libraries.

## ⚙️ 3. Setting up your Colab Environment with R packages (This step is also done in the notebook)

You can run these commands in your Colab notebook for required R packages installation (Setup):

```!R -e "install.packages(c('reticulate','dplyr','arrow'), repos='http://cran.us.r-project.org')" ``` 

```!R -e "remotes::install_github('LTREB-reservoirsvera4castHelpers')" ``` 




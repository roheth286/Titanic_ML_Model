# ⚙️ Titanic Survival Prediction (ML Task) 🚢

## 🎯 Project Goal  
This project builds a complete machine learning pipeline on the classic **Titanic** dataset to predict whether a passenger survived or not. The entire workflow is implemented in a **single Jupyter notebook**: loading the data from an external link, cleaning and preprocessing, performing exploratory data analysis (EDA), and training baseline classification models evaluated with **accuracy** and **F1‑score**.

---

## 🔬 Project Overview  

The notebook is organized into three main stages:

1. **Data Preparation**
   - Load the Titanic dataset using the download link provided inside the notebook.
   - Handle missing values and clean the data.
   - Encode categorical features and scale numerical data where needed.

2. **Exploratory Data Analysis (EDA)**
   - Generate general summary statistics.
   - Visualize survival patterns by passenger class and gender (bar and count plots).
   - Inspect age distributions by survival status (box plots).
   - Use plots to better understand the relationship between features and survival.

3. **Machine Learning Model**
   - Train basic classification model(s) to predict survival.
   - Evaluate model performance with **accuracy** and **F1‑score**.
   - Perform simple feature selection and basic tuning to improve results.

---

## 📊 Dataset  

- The dataset is **not stored in this repository**; instead, the notebook contains a **dataset link** that you must use to download the CSV file.  
- The target variable is `Survived` (0 = did not survive, 1 = survived).  
- Typical features include passenger class, sex, age, family relations, fare, and embarkation port.

> The exact download URL and required file name are specified inside the notebook in the “Import Dataset” section.

---

## 📁 Project Structure  

- `README.md` → Project description and usage instructions (this file).  
- `titanic_survival.ipynb` (or similarly named) → Main notebook containing the full ML pipeline, dataset link, and all analysis steps.

---

## 🚀 How to Run (Google Colab Only)  

This project is intended to be run **only in Google Colab**.

1. **Open the notebook in Colab**
   - Upload the `.ipynb` file to your Google Drive, then right‑click → **Open with → Google Colaboratory**,  
   - **or** open it directly from GitHub using Colab’s “Open in Colab” option (if you add the badge/link later).

2. **Download the dataset from the notebook link**
   - Scroll to the section labeled **“Import Dataset”** (or similar) in the notebook.  
   - Follow the link provided there to download the Titanic CSV file **locally to your machine** (e.g., `Downloads` folder).  
   - Return to the notebook and run the **“Import Dataset”** cell:
     - When it runs, it will prompt you to **upload a file**.  
     - Select the Titanic CSV you just downloaded.  
   - After this upload, the dataset will be available in the Colab session and the subsequent cells can access it.

3. **Run the notebook cells in order**
   - Run all cells in the **Data Preparation** section to:
     - Load the uploaded dataset.
     - Clean missing values and preprocess features.  
   - Run the **EDA** section to:
     - View summary statistics.
     - Generate bar, box, and count plots for survival analysis.  
   - Run the **Machine Learning** section to:
     - Train the classification model(s).
     - Compute accuracy and F1‑score.
     - Optionally explore simple feature selection and tuning if provided.

---

## 📄 Notes  

- All logic and dependencies are handled directly within the notebook and Colab environment.  
- If additional packages are required, they are installed via `pip` commands in the notebook cells.  
- Make sure to always upload the correct Titanic CSV file when prompted by the **Import Dataset** cell.

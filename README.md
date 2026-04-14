### May/June Pre-Intership Project: Healthcare Data Pipeline and Machine Learning System
---
Build a healthcare analytics system using a dataset from Kaggle. The system should clean and store the data in a PostgreSQL database and retrain a machine learning model every Saturday at 12:00 noon to predict patient test results as Normal, Abnormal, or Inconclusive.

Deploy the model using Flask or FastAPI, push your project to GitHub, host it on a free platform such as Vercel, and share the live API link. 

--- 

You can download the data directly from [Kaggle, https://www.kaggle.com/datasets/prasad22/healthcare-dataset/data](https://www.kaggle.com/datasets/prasad22/healthcare-dataset/data) or use the script below to download from kaggle hub: 

```python
import kagglehub

# Download latest version
path = kagglehub.dataset_download("prasad22/healthcare-dataset")

print("Path to dataset files:", path)****
```
You can learn how set up your API keys [here](https://www.kaggle.com/docs/api#authentication), to be able to interact programmatically with Kaggle dataset, https://www.kaggle.com/docs/api#authentication

- Incase you need help reach out directly via internship@luxdevhq.com or 0798166628 

---

#### **Project Overview.**
You are required to build an end-to-end healthcare data system using a synthetic dataset downloaded from Kaggle. The system should clean, store, and process healthcare data, and retrain a machine learning model every Saturday at 12:00 noon to predict patient test results.

**Project Objective:** By completing this project, you should be able to:
- Work with real-world structured datasets. 
- Clean and transform data using Python.
- Store data in a relational database (PostgreSQL).
- Build and retrain machine learning models.
- Deploy a prediction system as a live API.
- Use GitHub for version control and project sharing.

---   
**Dataset Instructions**
- Download the dataset,healthcare_dataset.csv, Healthcare Dataset (10,000 synthetic records)
- Load the dataset into Python using Pandas.
- Understand all columns before proceeding.

--- 

##### **Project Tasks**

**1. Data Ingestion**
- Load the dataset from Kaggle  
- Store a raw copy in your database  

**2. Data Cleaning & Transformation**

You must:
- Handle missing values  
- Remove duplicates  
- Convert date columns properly  
- Standardize categorical values  
- Drop irrelevant columns (e.g., Name, Doctor if necessary)  
- Prepare the dataset for machine learning  


--- 
- The deployed app should look like the one above: 

<img width="960" height="516" alt="image" src="https://github.com/user-attachments/assets/c2eb6912-d8de-4b78-a67e-d97e57509fe0" />









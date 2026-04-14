### May/June Pre-Intership Project:
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



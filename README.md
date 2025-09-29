# 🌸 Iris Flower Classification Project  

This project demonstrates a simple **Machine Learning workflow** using the **Iris dataset**.  
We follow the required structure: **Setup → Organize → Implement → Document**.  

The notebook is built and tested on **Google Colab**, and the final model achieves high accuracy using a **Random Forest Classifier**.  

---

## 📂 Project Structure  
ML_Colab_Project/
│── README.md
│── requirements.txt
│── .gitignore
│── notebooks/
│ └── iris_classification.ipynb

---

## ⚙️ Requirements  

Install all dependencies with:  
```bash
pip install -r requirements.txt

Main libraries used:
numpy
pandas
scikit-learn
matplotlib
joblib
(Colab already includes these by default.)

▶️ Running the Notebook
Option 1: Open in Colab
You can run the notebook directly in Google Colab:

Option 2: Run Locally
1. Clone the repo:

git clone https://github.com/BHAVI-HUDE/ML_Colab_Project.git
cd ML_Colab_Project

2.Install requirements:

pip install -r requirements.txt

3.Open Jupyter Notebook:

jupyter notebook notebooks/iris_classification.ipynb


📊 Results

Model: Random Forest Classifier
Accuracy: ~97-100% on test set
Outputs:
1.Classification report
2.Confusion matrix visualization
3.Saved model (iris_model.pkl)



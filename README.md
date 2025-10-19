# Detection of Higgs Boson Events Using Ensemble and Neural Network Models

The Higgs Boson was a groundbreaking discovery at CERN’s Large Hadron Collider (LHC), confirming the Standard Model's prediction of a mass-giving particle. However, distinguishing **rare Higgs signal events** from vast **background noise** remains a major computational challenge.

This project applies **machine learning techniques**, including **ensemble models (XGBoost, Gradient Boosting, Random Forest)** and a **Neural Network (MLPClassifier)**, to classify signal vs background events from proton-proton collision data.

Special optimization is performed using the **Approximate Median Significance (AMS)** – a high-energy physics metric for evaluating discovery potential.


## Objective
The goal of this project is to:
- Classify events as **Signal (s)** or **Background (b)**.  
- Improve detection of true signal events using advanced ML models.  
- Optimize classification with respect to **AMS score** rather than basic accuracy.  
## Tech Stack
- **Languages & Tools:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, SciPy  
- **ML Frameworks:** scikit-learn, Logistic Regression, Random Forest, Gradient Boosting, XGBoost, and Neural Network
- **Environment:** Jupyter Notebook / Google Colab

**How to run:**
1. Open `Code.ipynb` in Jupyter
2. Follow instructions in notebook
  
**Full project report:** [PDF](Method-Result.pdf)

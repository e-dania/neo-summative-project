# Near Earth Objects Classification Using Deep and Machine Learning  - Summative Project

**Date:** October 2025  
**Course:** Introduction to Machine Learning  
**Author:** Emmanuel Dania

---
## Project Context  
Near-Earth Objects (NEOs), such as asteroids and comets, pose a potential hazard to Earth, making their monitoring and classification a critical aspect of planetary defense. Early detection and accurate prediction of hazardous objects are essential to prevent catastrophic events, yet tracking and interpreting NEO characteristics can be challenging due to the vast number of objects and the complexity of orbital data.
## Problem Statement  
Key NEO characteristics — including miss distance, relative velocity, estimated diameter, and absolute magnitude — influence whether an object is potentially hazardous. However:

* The dataset is imbalanced, with far fewer hazardous objects than non-hazardous ones
* Accurate hazard prediction is critical for risk assessment and mitigation planning
* Traditional methods for classification may struggle to capture nonlinear relationships between features
## Solution
I developed an automated NEO hazard classification system using both traditional machine learning and deep learning techniques. The goals are to:
* Predict the likelihood of a NEO being potentially hazardous
* Identify the most important physical features contributing to hazard risk
* Provide interpretable predictions for planetary defense decision-making
* Explore scalable deep learning pipelines for future, larger datasets

---
## Dataset Overview
**Source:** NASA Near-Earth Object dataset (Kaggle)  
**Size:** 27423 (before preprocessing),  
**Features:**   
* Estimated minimum diameter (est_diameter_min)  
* Estimated maximum diameter (est_diameter_max)  
* Relative velocity (relative_velocity)  
* Miss distance (miss_distance)  
* Absolute magnitude (absolute_magnitude)    
**Target Class:** Binary classification (Hazardous vs Non-Hazardous)  
**Labels:** Defined based on NASA’s hazard designation

  ---

## 🛠️ Installation & Setup

### Prerequisites
- Python 3.8 or higher
- Jupyter Notebook or Google Colab
- Git

### Step 1: Clone Repository
```bash
git clone https://github.com/e-dania/neo-summative-project.git
cd neo-summative-project
```

### Step 2: Create Virtual Environment (Recommended)
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### Step 4: Launch Jupyter Notebook
```bash
jupyter notebook Near_Earth_Objects_Classification_Using_Deep_and_Machine_Learning_Summative_Project.ipynb
```

### Required Libraries
```txt
numpy>=1.21.0
pandas>=1.3.0
matplotlib>=3.4.0
seaborn>=0.11.0
scikit-learn>=1.0.0
imbalanced-learn>=0.9.0
xgboost>=1.5.0
tensorflow>=2.8.0
```

##  Demo Video

 **[Watch My Project Demo](https://drive.google.com/file/d/1aJqfrXYqTTGqatFIkyfQ0NZ74OnqX5mZ/view?usp=sharing)**



##  Documentation

### Written Report
 **[Written Report (PDF)](https://docs.google.com/document/d/1MYb5RrAPSLHw8toBbiYh9gRjc8Ag9iwutT0o3YAWJbg/edit?usp=sharing)** -


---

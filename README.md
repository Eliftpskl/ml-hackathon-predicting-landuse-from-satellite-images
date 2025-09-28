# Machine Learning Hackathon – Predicting Land Use from Satellite Images 🛰️

This repository contains my project from the **Second Hackathon of the Machine Learning course**.  
The goal was to **classify satellite images into land use categories** using deep learning models.  
The project was organized as a Kaggle competition, where teams submitted predictions and were ranked by **Accuracy**.

---

## Project Overview
- **Task:** Image Classification – Predict the land use category of a given satellite image.  
- **Data:**  
  - EuroSAT dataset (https://github.com/phelber/EuroSAT)  
  - 18,000 labeled training images (64×64 px)  
  - 9,000 test images  
  - 10 classes (annual crop, forest, river, highway, …)  
- **Goal:** Achieve an accuracy higher than the simple CNN benchmark (Accuracy = 0.7845).  

---

## Methods & Models
- Image preprocessing and normalization.  
- Data augmentation to improve generalization.  
- Tried multiple approaches, including:  
  - Baseline CNN  
  - Transfer learning with **EfficientNetB0**  
  - Regularization (dropout, weight decay) and learning rate scheduling  
  - Ensembling of models for better accuracy  
- Hyperparameter tuning with different optimizers and batch sizes.  

---

## Results
- Successfully achieved accuracy above the CNN baseline.  
- Best submission placed competitively on the Kaggle leaderboard.  
- Demonstrated experience in deep learning, transfer learning, and image classification tasks.  

---

## Repository Structure
```
.
├── hyperparamaniacs-efficientnetb0-hackathon2.ipynb # Jupyter notebook with code & results
├── README.md # Project description
├── requirements.txt # Dependencies
└── .gitignore # Ignore unnecessary files

```


---

## How to Run

1. Clone the repository:
   ```bash
   git clone https://gitlab.com/Eliftpskl/ml-hackathon2-landuse.git
   cd ml-hackathon2-landuse
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
3. Open the notebook:
   ```bash
   jupyter notebook hyperparamaniacs-efficientnetb0-hackathon2.ipynb

## Kaggle Competition & Notebook

This project was part of the **[UMR-ML-2025 Hackathon 2](https://www.kaggle.com/competitions/umr-ml-2025-hackathon-2)** on Kaggle.  
You can view and run the notebook here:  
👉 [Hackathon2 — Satellite Land Use Classification](https://www.kaggle.com/code/eliftpskl/hackathon2-satellite-landuse)

   

# Review-Analysis-on-Clothing-Items
This project focuses on analyzing user reviews of clothing items for men, women, and children to determine the sentiment (positive, neutral or negative) expressed in the reviews. It applies data mining techniques and machine learning models, particularly Support Vector Machine (SVM), to classify sentiments based on textual data.
## Objectives:
- Collect and organize review data for clothing items across genders.
- Clean, merge, and preprocess the review data.
- Train machine learning models (SVM) to classify review sentiments.
- Evaluate model performance using classification metrics.
- Document the methodology, challenges, and findings.
  
## Dataset:
The dataset consists of manually compiled user reviews collected by multiple contributors. Each review contains:
- Textual feedback on clothing items
- Sentiment labels (Positive, Neutral, Negative)
- Possibly metadata such as item type, gender, or age group
  
## File Overview:

This project includes the following files:

| File Name                          | Description |
|-----------------------------------|-------------|
| **`SVM.ipynb`**                   | A Jupyter Notebook implementing a Support Vector Machine (SVM) model for sentiment analysis on clothing reviews. Includes preprocessing, training, and evaluation. |
| **`Merged data.xlsx`**           | A unified dataset containing merged review data from all contributors. Used as input for modeling. |

## Model Evaluation:    
The SVM model is evaluated using:
Accuracy
Precision, Recall, and F1 Score
Confusion Matrix
Classification Report

Visualizations are provided to better understand the classification results and performance comparison.

##  Tools and Libraries:
To run this project, make sure the following Python libraries are installed:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn nltk openpyxl


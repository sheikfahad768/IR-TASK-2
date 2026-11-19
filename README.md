# INFORMATION RETRIEVAL – TASK 2
## TEXT CLASSIFICATION BATTLE
### Compare, Analyze and Defend: A Machine Learning Text Classification Study

**Student Name:** SHEIKH FAHAD M A  
**Register Number:** RA2411026050181  
**Class:** CSE-AIML C  
**Course:** Information Retrieval  
**Institution:** SRM Institute of Science and Technology

---

## 1. Project Overview

This project explores text classification using the BBC News dataset. The objective is to classify news articles into five categories—Business, Entertainment, Politics, Sport, and Tech—and compare the performance of four machine-learning classifiers.

## 2. Objectives

- Load and explore the BBC News dataset.
- Preprocess the text data for machine learning.
- Convert text into numerical features using TF-IDF vectorization.
- Train and evaluate four classification algorithms.
- Compare model performance using accuracy, precision, recall, and F1-score.
- Visualize model performance using confusion matrices and comparison graphs.
- Conduct a what-if experiment to investigate the effect of changing the K-Nearest Neighbors (KNN) parameter.
- Analyze the results and defend the selection of the best-performing model.

## 3. Dataset

**Dataset:** BBC News  
**File:** `BBC News Train.csv`

The dataset contains the article text and its category label. The five categories are Business, Entertainment, Politics, Sport, and Tech.

## 4. Machine-Learning Models

1. Decision Tree Classifier
2. K-Nearest Neighbors (KNN)
3. Support Vector Machine (SVM)
4. Multinomial Naive Bayes

## 5. Evaluation Approach

The workflow uses an 80:20 train-test split, TF-IDF feature extraction, and evaluation with accuracy, precision, recall, and F1-score. Confusion matrices and comparison graphs are included in the notebook.

## 6. Recorded Model Results

The original notebook and project documentation report the following results for the recorded experiment:

| Model | Accuracy | Macro F1-score |
|---|---:|---:|
| Decision Tree | 82.89% | 82.40% |
| KNN (K=5) | 92.28% | 91.93% |
| Linear SVM | 97.65% | 97.55% |
| Multinomial Naive Bayes | 97.65% | 97.57% |

Results apply to the recorded dataset split and settings; they may differ when the notebook is rerun in a different environment.

## 7. What-If Experiment: KNN

The KNN model was tested with K values of 3, 5, 7, 9, and 11. In the recorded results, K=9 and K=11 tied for the highest accuracy (93.62%), while K=11 produced the highest Macro F1-score (93.41%).

## 8. Conclusion

The project demonstrates a text-classification workflow using TF-IDF and four machine-learning algorithms. In the recorded experiment, Linear SVM and Multinomial Naive Bayes achieved the strongest overall performance. The KNN experiment showed that changing the number of neighbours affected classification performance. Model selection should consider relevant evaluation metrics rather than accuracy alone.

## 9. How to Run

1. Open `IR TASK 2.ipynb` in Google Colab or Jupyter Notebook.
2. Upload `BBC News Train.csv` when prompted.
3. Run the notebook cells from top to bottom.
4. Review the comparison table, confusion matrices, and KNN experiment outputs.

**Requirements:** Python 3, pandas, scikit-learn, matplotlib, seaborn, and Google Colab or Jupyter Notebook.

## 10. Project Source and Attribution

This individual submission is adapted from the project structure and materials in the original repository:

https://github.com/sivabalan718/IR-TASK-2

Original project contributions are acknowledged. The dataset and notebook workflow have been retained, while the submission identity above has been updated.

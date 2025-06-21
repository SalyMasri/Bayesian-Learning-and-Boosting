# Naïve Bayes, Boosting & Decision Boundaries

## Project Overview
This project investigates **Naïve Bayes classification**, **Boosting**, and **Decision Tree ensembles** for improving classification accuracy. It evaluates the **bias-variance tradeoff**, the effect of boosting iterations, and training data splits on **Iris and Vowel datasets**.

## Technologies & Tools Used
- **Programming Language**: Python
- **Libraries**: NumPy, Matplotlib, Scikit-learn
- **Algorithms**: Naïve Bayes, Decision Trees, AdaBoost
- **Evaluation Metrics**: Classification Accuracy, Decision Boundaries, Model Complexity

## Key Features

### Naïve Bayes & Feature Independence
- **Analyzed feature independence assumptions** in the Iris dataset.
- **Explored decision boundary limitations** in linear models.
- **Compared different feature transformations** to improve separability.

### Boosting for Classification Improvement
- **Implemented AdaBoost** on Naïve Bayes & Decision Trees.
- **Tracked accuracy improvement** over boosting iterations.
- **Plotted decision boundary evolution** before and after boosting.

### Training Data Split & Model Generalization
- **Tested different training data proportions** to assess learning stability.
- **Evaluated overfitting risks** in boosted models.
- **Compared classifier performance (SVM, KNN, Random Forests)** on multiple datasets.

## Results
- **Boosting significantly improves accuracy**, especially for complex datasets.  
- **Naïve Bayes is effective but limited by feature independence assumptions**.  
- **Decision Trees benefit from boosting**, but require **pruning** to prevent overfitting.  
- **Training data splits impact performance**, with 30%-60% offering optimal results.  

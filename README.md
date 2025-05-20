# Obesity Insight Predictor  
*CS 412: Introduction to Machine Learning — Final Project (Fall 2024)*  
University of Illinois Chicago (UIC)

## About This Project

This machine learning project was developed as part of the CS 412 course at UIC, aimed at predicting obesity risk based on lifestyle and demographic factors. Using a dataset of 2,111 entries and 17 features (e.g., dietary habits, physical activity, transportation), we trained and evaluated several classification models to accurately predict a person's obesity level.

## Models Implemented

We tested and compared the performance of:
- **Naive Bayes**
- **Support Vector Classifier (SVC)**
- **Voting Ensemble Classifier** (combining Random Forest, SVC, and Gradient Boosting)

Our best-performing model — the ensemble — achieved up to **98% accuracy** and **F1-scores as high as 1.00** across multiple obesity categories.

## My Contributions

While this was a collaborative team project, this fork highlights **my individual contributions**, which include:
- Writing and refining the `dataCleaning.py` script used for preprocessing the dataset
- Training and evaluating machine learning models in Jupyter/Colab
- Analyzing performance using confusion matrices and classification reports
- Synthesizing results for our final report and class presentation

> **Note:** Much of our collaborative work took place in **Google Colab**, so the original GitHub commit history does not fully reflect my role. This fork serves to showcase the parts of the project I personally contributed to and understand deeply.

## Tools & Libraries
- Python, Jupyter Notebook  
- scikit-learn, pandas, matplotlib, seaborn  
- Ensemble models via `VotingClassifier` from `sklearn.ensemble`

## Dataset Summary
- 2,111 records with 17 features
- BMI range: 13.0 to 50.8
- Labels: 7 multiclass obesity levels including "Normal Weight", "Obesity Type I", etc.

## Project Structure
```
├── dataCleaning.py # Custom data preprocessing script
├── CS412Project.ipynb # Main notebook (model training + evaluation)
├── ObesityDataSet.csv # Dataset used for training/testing
├── Final Report + Slides # PDF deliverables from class (in /docs or root)
```
## 🙋‍♀️ About Me
Hi! I’m Srijita Banerjee, a recent Computer Science graduate from UIC passionate about applying ML to meaningful, real-world problems.  
This project was an early but important step in my journey into machine learning, and I’m proud of what we built as a team.

📫 [Reach out to me](mailto:banerjeesrj@gmail.com) or connect via [LinkedIn](https://www.linkedin.com/in/srijitabanerjee)

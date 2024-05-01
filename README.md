# Disease Prediction Using Machine Learning
<p>This repository contains code for predicting diseases using machine learning algorithms based on symptoms.</p>

### Introduction
<p>This project focuses on predicting diseases based on symptoms using machine learning techniques. It involves preprocessing the dataset, training multiple machine learning models, evaluating their performance, and creating a combined model for accurate predictions.
</p>

### Requirements
<ul><li>Python 3.x</li>
<li>Jupyter Notebook or any Python IDE</li>
<li>Libraries: numpy, pandas, scipy, matplotlib, seaborn, scikit-learn</li></ul>

### Dataset
<p>The dataset used for training and testing is located in the dataset directory. It includes information about various symptoms and corresponding diseases.</p>

### Usage
<ol><li>Clone the repository:</li>
  
```
git clone https://github.com/username/repo.git
```

<li>Navigate to the repository directory:</li>

```
cd repo
```

<li>Run the Jupyter Notebook Disease_Prediction.ipynb to see the code in action.</li></ol>

### Workflow
<ul><li>Data Preprocessing: The dataset is loaded and preprocessed to handle missing values and encode categorical variables.</li>
<li>Model Training: Several machine learning models, including Support Vector Classifier (SVC), Naive Bayes, and Random Forest Classifier, are trained on the dataset.</li>
<li>Model Evaluation: The trained models are evaluated using k-fold cross-validation to assess their performance.</li>
<li>Combined Model: A combined model is created by taking the mode of predictions from individual classifiers for improved accuracy.</li>
<li>Prediction Function: A function is defined to predict diseases based on input symptoms. It utilizes the combined model for predictions.</li></ul>

### Results
- Model Performance: All models achieved 100% accuracy on both training and testing datasets.
- Combined Model: The combined model also achieved 100% accuracy on the test dataset.
- Prediction Function: The provided function accurately predicts diseases based on input symptoms.

### Example

```
print(predictDisease("Itching,Skin Rash,Nodal Skin Eruptions"))
# Output: {'rf_model_prediction': 'Fungal infection', 'naive_bayes_prediction': 'Fungal infection', 'svm_model_prediction': 'Fungal infection', 'final_prediction': 'Fungal infection'}
```
### Contributing
Contributions are welcome! Please feel free to submit issues and pull requests.

### License
<p>This project is licensed under the MIT License.</p>

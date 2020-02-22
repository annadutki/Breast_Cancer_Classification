## Breast_Cancer_Classification
### Description

**The aim is to predict if the cancer diagnosis is benign or malignant based on several features**

30 features are used: radius, texture, perimeter, area, smoothness, compactness, concavity, concave points, symmetry, fractal dimension, radius, texture, perimeter, area, smoothness, compactness, concavity, concave points, symmetry, fractal dimension, radius, texture, perimeter, area, smoothness, compactness, concavity, concave points, symmetry, fractal dimension.

Missing Attribute Values: None

Number of Instances: 569

Class Distribution: 212 - Malignant, 357 - Benign

Target class:
   - Malignant (0)
   - Benign (1)

Data information: https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic)

### Workflow
1. Data import
- Load libraries
- Load dataset
- Create dataframe
2. Data visualizing
- Data overview on the example of 5 features where 0 - malignant, 1 - benign
- Print correlation matrix
3. Model training
- Define feature (inputs) and target (output) values
- Train data using SVC
4. Model evaluating
- Test data using SVC
- Print confusion matrix
- Print heatmap
- Print classification report
5. Model improving
- Normalize data
- Train scaled data using SVC
- Test scaled data using SVC
- Print confusion matrix
- Print heatmap
- Print classification report
6. Model further improving
- Define grid parameters
- Train scaled data using SVC
- Print best parameters
- Test scaled data using SVC
- Print confusion matrix
- Print heatmap
- Print classification report

### Conclusions
1. Using SVM machine learning technique we were able to classify cancer type with 97% accuracy
2. Misclassified samples were all type 1 errors which means that the patients had cancer but cancer was just benign, not malignant as per classification

### Acknowledgements
This implementation was inspired by Kirill Eremenko, Hadelin de Ponteves, Dr. Ryan Ahmed, Ph.D., MBA, SuperDataScience Team, Rony Sulca [Machine Learning Practical Udemy course](https://www.udemy.com/course/machine-learning-practical/?utm_source=adwords&utm_medium=udemyads&utm_campaign=DataScience_v.PROF_la.EN_cc.ROW_ti.5336&utm_content=deal4584&utm_term=_._ag_85469003954_._ad_395279056268_._kw__._de_c_._dm__._pl__._ti_dsa-774930036449_._li_1011367_._pd__._&matchtype=b&gclid=CjwKCAiAvonyBRB7EiwAadauqdGsq1pYwJXPHmZpdR12WWHTeI31ZGNAR7wJqhrnln_dI452sQCbCBoCnvwQAvD_BwE)

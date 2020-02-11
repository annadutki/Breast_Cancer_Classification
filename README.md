## Breast_Cancer_Classification
### Description

**The aim is to predict if the cancer diagnosis is benign or malignant based on several features**

30 features are used:radius, texture, perimeter, area, smoothness, compactness, concavity, concave points, symmetry, fractal dimension, radius, texture, perimeter, area, smoothness, compactness, concavity, concave points, symmetry, fractal dimension, radius, texture, perimeter, area, smoothness, compactness, concavity, concave points, symmetry, fractal dimension.

Missing Attribute Values: None

Number of Instances: 569

Class Distribution: 212 - Malignant, 357 - Benign

Target class:
   - Malignant (0)
   - Benign (1)

Data information: https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic)

### Workflow
1. Data import
- Load libraries (pandas, numpy, matplotlib, seaborn)
- Load dataset
2. Data visualizing
- Use pairplot to show the relations between different variables, few default features were chosen
- Use countplot to count the samples
- Plot the correlation matrix to see the correlations between the features
3. Model training
- Define input/ output values
- Split data into train and test data
- Train data using SVC
4. Model evaluating

### Acknowledgements
This implementation was inspired by Kirill Eremenko, Hadelin de Ponteves, Dr. Ryan Ahmed, Ph.D., MBA, SuperDataScience Team, Rony Sulca [Machine Learning Practical Udemy course](https://www.udemy.com/course/machine-learning-practical/?utm_source=adwords&utm_medium=udemyads&utm_campaign=DataScience_v.PROF_la.EN_cc.ROW_ti.5336&utm_content=deal4584&utm_term=_._ag_85469003954_._ad_395279056268_._kw__._de_c_._dm__._pl__._ti_dsa-774930036449_._li_1011367_._pd__._&matchtype=b&gclid=CjwKCAiAvonyBRB7EiwAadauqdGsq1pYwJXPHmZpdR12WWHTeI31ZGNAR7wJqhrnln_dI452sQCbCBoCnvwQAvD_BwE)

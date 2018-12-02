# Feature-Selection-Without-Domain-Expertise-And-Resampling-Techniques
Realize Several Feature Selection Methods without Haveing Domain Expertise and Realize Two Classes of Resampling Techniques

### 1. Feature Selection Methods

* Removing Features with Low Variance(Useful for Prescreened the Large Variables Set)    
* Univariate Feature Selection
* Recursive Feature Elimination(Running Time and Accuracy Trade off)   
* Feature Selection Using SelectFromMode

What can we do if there are still too many variables after using feature selection methods above?

### 2. Resampling Techniques
* Random Over-sampling
* Synthetic Minority Over-sampling Technique(SMOTE)

***
The SMOTE oversamples the rare event by using bootstrapping and k-nearest neighbor to synthetically create additional observations of that event. The definition of rare event is usually attributed to any outcome/dependent/target/response variable that happens less than 15% of the time.
***

Next several things I want to add to this repository are the methods of missing value imputation and the methods of converting categorical variables to numerical variables. I will come back to this later.

### 3. Missing Value Imputation Methods
* Mean and Median Imputaion
* Multiple Imputaion by Chained Equations
* EM Imputation
* Other Imputation Methods

Advantages and disadvantages (Comparison) among the methods listing above

### 4. Methods of Converting Categorical Variables to Numerical Variables
* Dummy Variable Method(For Nonbinary Variable Method)
* One-hot Encoding
* LabelEncoder(Scikit-learn)

Advantages and disadvantages (Comparison) among the methods listing above

### 5. Methods of Parameter Tuning
* Grid Search with Cross Validation
* Randomized Search with Cross Validation

Advantages and disadvantages (Comparison) among the methods listing above

### 6. Feature Generation and Auto Model Training
* Featuretools Module in Python: Featuretools is a python library for automated feature engineering

References:  
a. https://github.com/Featuretools/featuretools     
b. https://docs.featuretools.com/

* AutoML: Automated machine learning for production and analytics

References:  
a. https://auto-ml.readthedocs.io/en/latest/  
b. https://pypi.org/project/automl/   
c. https://github.com/automl  
d. https://www.kdnuggets.com/2017/01/current-state-automated-machine-learning.html

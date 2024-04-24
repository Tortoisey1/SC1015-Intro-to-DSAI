# Welcome to the Lego Repository

![Ferarri Daytona SP3](https://blogger.googleusercontent.com/img/a/AVvXsEiMZx3MfZFUS8eF4G2fBE_3wgcamEZdYeqGwmAMC-C6ekITkh2uYQhCVQ_vw_IDhVUa18OAzMADyJYl45LvoclM2s_5xIhPu_JvJOMONqWGH8nC--6mvRAfWGYXYBUG6H_wqtiIpKW7GJ7yXL1DNrrZDm74eMQvCJptXGPH3eRIPAK84zplWRtX83K3mg=w640-h360)


## About
This is a Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence), focusing on analyzing lego data from Sets from https://www.kaggle.com/datasets/willianoliveiragibin/lego-sets-and/data . For a detailed walkthrough, For a detailed walkthrough, please view the source code in the [Mini Project Python notebook](https://github.com/Tortoisey1/SC1015-Intro-to-DSAI/blob/main/Mini%20Project.ipynb).

## Contributors
- **Noel Tan**
- **Issac Goh**

## Problem Definition
- Are we able to predict if a Rating is good based on its attributes?
- Which model would be the best to predict it?

## Models Used
- **Decision Tree**
- **Random Forest**
- **Cross Validation Grid Search**

## Conclusion
- Ratings can be predicted using theme, number of pieces, prices and number of minifigures.
- Resampling imbalanced data improved model performance, especially on the minority class.
- Basic decision tree did not perform well without any change to parameters.
- Random forest, along with cross validation Grid Search, has higher accuracy at predicting ratings (around 88% accuracy, 20% false negative).
- Yes, it is possible to predict if a lego set is good with an acceptable amount of accuracy.

## What Did We Learn From This Project?

Throughout this project, we gained practical experience and insights into several key areas of data science and machine learning:

- **Handling Imbalanced Datasets:**
  - Developed skills in managing imbalanced data, specifically using the oversampling method to enhance the representativeness of minority classes in our dataset.

- **Exploring Machine Learning Methods:**
  - **Random Forest:** Gained proficiency in implementing and tuning Random Forest models to improve prediction accuracy.
  - **Cross-Validation Grid Search:** Learned to use grid search techniques within a cross-validation framework to find the best model parameters, thereby optimizing model performance.
  - **Advanced Data Visualization:** Introduced to new plotting functions in Plotly, enhancing our ability to create interactive and highly informative visual representations of our data.

- **Collaboration Tools:**
  - Enhanced our collaboration skills by using GitHub, which facilitated effective teamwork and version control throughout the project.



## References

1. **Scikit-Learn - RandomForestClassifier Documentation**  
   "sklearn.ensemble.randomforestclassifier¶." [Online]. Available: [Scikit-Learn RandomForest](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html). [Accessed: 21-Apr-2021].

2. **R. Meinert - Optimizing Hyperparameters in Random Forest Classification**  
   Medium, 07-Jun-2019. [Online]. Available: [Medium Article by R. Meinert](https://towardsdatascience.com/optimizing-hyperparameters-in-random-forest-classification-ec7741f9d3f6). [Accessed: 21-Apr-2021].

3. **M. Sharma - Grid Search for Hyperparameter Tuning**  
   Medium, 21-Mar-2020. [Online]. Available: [Medium Article by M. Sharma](https://towardsdatascience.com/grid-search-for-hyperparameter-tuning-9f63945e8fec). [Accessed: 21-Apr-2021].

4. **Scikit-Learn - GridSearchCV Documentation**  
   "sklearn.model_selection.GridSearchCV¶." [Online]. Available: [Scikit-Learn GridSearchCV](https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.GridSearchCV.html). [Accessed: 21-Apr-2021].

5. **J. Brownlee - Hyperparameter Optimization With Random Search and Grid Search**  
   Machine Learning Mastery, 18-Sep-2020. [Online]. Available: [Machine Learning Mastery by J. Brownlee](https://machinelearningmastery.com/hyperparameter-optimization-with-random-search-and-grid-search/). [Accessed: 21-Apr-2021].

6. **Shahul ES - Hyperparameter Tuning in Python: a Complete Guide 2021**  
   Neptune.ai, 19-Mar-2021. [Online]. Available: [Neptune.ai Blog](https://neptune.ai/blog/hyperparameter-tuning-in-python-a-complete-guide-2020#:~:text=Hyperparameter%20tuning%20is%20the%20process,maximum%20performance%20out%20of%20models). [Accessed: 21-Apr-2021].

7. **R. Joseph - Grid Search for model tuning**  
   Medium, 29-Dec-2018. [Online]. Available: [Medium Article by R. Joseph](https://towardsdatascience.com/grid-search-for-model-tuning-3319b259367e). [Accessed: 21-Apr-2021].

8. **Stack Overflow - Interpreting sklearns' GridSearchCV best score**  
   01-Feb-1967. [Online]. Available: [Stack Overflow](https://stackoverflow.com/questions/50232599/interpreting-sklearns-gridsearchcv-best-score). [Accessed: 21-Apr-2021].

9. **H. M. Mujtaba - What is Cross Validation in Machine learning? Types of Cross Validation**  
   GreatLearning Blog, 24-Sep-2020. [Online]. Available: [GreatLearning Blog by H.M. Mujtaba](https://www.mygreatlearning.com/blog/cross-validation/). [Accessed: 21-Apr-2021].

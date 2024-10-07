# Bertelsmann/Arvato

### Project Summary:

Demographics data of customers of a mail-order sales company in Germany is analyzed in the project. The approach is to compare the data of the population with the customers using unsupervised learning techniques to obtain insights on customer profiles. Subsequently, supervised learning techniques are used to predict whether or not a an individual should be targeted in the context of a marketing campaign. 

### Motivation

The project is part of the Data Scientist Nanodegree offered by Udacity. As a student, you are allowed to choose between different projects. I chose the Bertelsmann/Arvato capstone, because it comprises a lot of relevant aspects of the Data Science workflow to a sufficient extent, esp. working with real life data. Data investigation, cleaning, preprocessing, scaling as well as unsupervised (dimensionality reduction and clustering) and supervised learning techniques are part of it, which makes it very comprehensive and therefore an attractive choice to cover a lot of the Data Science toolbox.  

### Data Files Used:

- `Udacity_AZDIAS_052018.csv`: Demographics data for the general population of Germany; 891 211 persons (rows) x 366 features (columns).
- `Udacity_CUSTOMERS_052018.csv`: Demographics data for customers of a mail-order company; 191 652 persons (rows) x 369 features (columns).
- `Udacity_MAILOUT_052018_TRAIN.csv`: Demographics data for individuals who were targets of a marketing campaign; 42 982 persons (rows) x 367 (columns).
- `Udacity_MAILOUT_052018_TEST.csv`: Demographics data for individuals who were targets of a marketing campaign; 42 833 persons (rows) x 366 (columns).

### Files in the repository
 
Arvato Project_SL.ipynb: the jupyter notebook containing the entire analysis.

### Project Structure:
- Part 0: Get to Know the Data
    - EDA
    - NaN investigation
    - Data Cleaning
    - One Hot Encoding
- Part 1: Customer Segmentation Report
    - Data Scaling and Imputation
    - Dimensionality Reduction using PCA
    - Clustering using Kmeans
    - Comparison General Population and Customers
    - Analysis of Overrepresented Clusters
- Part 2: Supervised Learning Model
    - Majority Classifier and Naive Prediction
    - Comparison of supervised learning technqiues
    - Fine Tuning of selected algorithm
    - Predictions on test set

### Project Results

Please see the following (blog post)[https://medium.com/@slietz/customer-segment-analysis-arvato-financial-services-22cfef589027]

### Acknowledgements:

**Udacity** for setting up this awesome project in their [Data Scientist Nanodegree](https://www.udacity.com/course/data-scientist-nanodegree--nd025?promo=year_end&coupon=SKILLS50&utm_source=gsem_brand&utm_medium=ads_r&utm_campaign=19167921312_c_individuals&utm_term=143524475679&utm_keyword=data%20scientist%20udacity_e&utm_source=gsem_brand&utm_medium=ads_r&utm_campaign=19167921312_c_individuals&utm_term=143524475679&utm_keyword=data%20scientist%20udacity_e&gad_source=1&gclid=EAIaIQobChMIlNyctJC_hgMVJ6loCR3eowY6EAAYASAAEgJhzPD_BwE).

**Bertelsmann/Arvato** for providing the data.

### Carleton Artifical Intelligence Society Kaggle Competitiono

#### Dependencies:
* [NumPy](http://www.numpy.org/)
* [IPython](http://ipython.org/)
* [Pandas](http://pandas.pydata.org/)
* [SciKit-Learn](http://scikit-learn.org/stable/)
* [Seaborn](https://seaborn.pydata.org/)
* [Matplotlib](http://matplotlib.org/)

#### Files:
* exploration.ipynb
  * In this file I explored the data given to get a better understanding of its structure and the possible correlations that exist
* dataPreprocessing.ipynb
  * This file preprocesses the data, encoding variables and dropping useless data, I then exported test and train to two pickle files
* test_data_preprocessed.pkl/train_data_preprocessed.pkl
  * The output of dataPreprocessing.ipynb, and the input to model.ipynb
* model.ipynb
  * Includes my best performing model, it uses hyperparameter tuning on a random forest regressor

#### This Notebook shows basic examples of:
#### Data Handling
*   Importing Data with Pandas
*   Cleaning Data
*   Exploring Data through Visualizations with Matplotlib + Seaborn

#### Data Analysis
*    Creating a hyperparameter tuned random forest regressor model

#### Valuation of the Analysis
*   K-folds cross validation to valuate results locally
*   Output the results from the IPython Notebook to csv for Kaggle Submission

Competition Website: https://www.kaggle.com/competitions/caisx

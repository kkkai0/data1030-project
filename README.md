# Introduction
Mushroom edibility prediction is to determine whether a mushroom is edible or poisonous based on various characteristics. This process is crucial for public health, ecological understanding, and the advancement of mycology and technology.

I obtained the dataset from Kaggle (which illustrates that the data is collected from Patrick Hardin, Mushrooms & Toadstools and Jeff Schlimmer, Mushroom Data Set). This dataset includes 61069 hypothetical mushrooms with caps based on 173 species (353 mushrooms per species). Each mushroom is identified as definitely edible, definitely poisonous, or of unknown edibility and not recommended (the latter class was combined with the poisonous class). Of the 20 variables, 17 are nominal and 3 are metrical. The target variable is“class”, which indicates mushroom edibility with “p” (poisonous) and “e” (edible) (with the former one also containing mushrooms of unknown edibility). In Kaggle, someone has used Random Forest to predict the problem and achieved a high accuracy score of 100%. 

# Prerequisites
I use python 3.7 for this project and here are some packages installed in advance:
Numpy, Pandas, Matplotlib, Seaborn, Sklearn, Shap

# Author

Zhikai Zhao (zhikai_zhao@brown.edu)

# License

This project is licensed under the MIT License.

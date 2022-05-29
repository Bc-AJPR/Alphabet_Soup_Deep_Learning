# Alphabet_Soup_Deep_Learning
<p align="center">
  <img src=".\Images\yes_pic.jpg" />

## Overview:
This analysis aims to predict whether or not an applicant will be successfully funded by Alphabet Soup, using a neural network machine learning model to create a binary classifier that is capable of predicting using the features collected in the provided dataset.
</p>


## The Process
Seeking accuracy of 75%  four models were run, changes in the number of neurons(units), the number of hidden layers, and dropping a different set of columns. 
These are the sets for each model:
### Original Model
<p align="left">
  <img src=".\Images\original_set.jpg" width="400"/>
</p>
<p align="left">
  <img src=".\Images\original_res.jpg" />
</p>

### Optimization 1
<p align="left">
  <img src=".\Images\Opt1_set.jpg" width="400"/>
</p>
<p align="left">
  <img src=".\Images\Opt1_res.jpg" />
</p>

### Optimization 2
<p align="left">
  <img src=".\Images\Opt2_set.jpg" width="400"/>
</p>
<p align="left">
  <img src=".\Images\Opt2_res.jpg" />
</p>

### Optimization 3
<p align="left">
  <img src=".\Images\Opt3_set.jpg" width="400"/>
</p>
<p align="left">
  <img src=".\Images\Opt3_res.jpg" />
</p>


## Summary
Although four models with different amounts of hidden layers and neurons and features were run, the models did not yield the seeking target; the best accuracy is 73.59% on the train and 73.17% on the test data set. Perhaps, Supervised models like Logistical, RandomForest, or AdaBoost Classifier would provide better results.
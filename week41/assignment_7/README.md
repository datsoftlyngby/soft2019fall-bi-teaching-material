####Assignment 7
#Basic ML - Class Prediction

One of the biggest challenges in real estate broking is -- not surpringly -- correct pricing. 

## Multi-class models.

In this assignment we return to the Boliga data. The objective is to build a classification machine learning model in Azure Machine Learning Studio (AML) from scratch. You will try to predict whether an estate sale will sell at over, at, or under the broker's initial pricing. What does that amount to? It amounts to a multi-class model.

How many classes do we have for this business case question? 

Put the answer in your hand-in and argue about what other good business questions could be posed from the Boliga data.

### Part 1: Data processing
Get the Boliga data and geolocations into an AML account of your group, with the geolocations too. You will need to work on the target variable (class label) as it is an integer -- but should be categorical. Is the data clean, meaningful, well formed?

### Part 2: ML model selection and construction 
In AML, build a three-level classification model with the objective of predicting whether a housing sale price was adjusted downwards, upwards, or not adjusted. 

### Part 3: Training & Validation
With your _training_ and _test_ data set, train your model and validate it. Determine its performance by inspecting the ROC curve in AML.

### Part 4: House Keeping
Clean up your work space when you're done. You don't want unnecessary waste of resources, which you might want to use at a later time. 

## Hand-in Procedure

  * Hand-in a link to the **release** on Peergrade.
  * The hand-in (on Peergrade) should be a link to a GitHub **release** containing _sufficient_: 
    - plots and screenshots of various visualizations
    - written text on findings and conclusions 
    for the assignment parts, to convince me that you pulled through.
  * Hand-in at latest on Wednesday Oct. 23rd, 2019, 08:30.
  * Hand-in as groups! Work as groupS, groUPS, GROUPS!  :o) 

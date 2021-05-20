# Machine Learning Notes

## Lecture 1: (1.1)


Machine learning
  ~ Teaching machine what comes naturally to humans/animals
  ~ Posteriori knowledge driven, learning from experiences


### Solve Real World Problems

1. Energy Production
2. Computer Vision and image processing
3. Computational Biology
    - DNA sequencing

#### Supervised Learning
    
    1. A model is trained to accept an input and and output

#### Unsupervised Learning 
    1.  Find intrinsic or hidden features of the data (i.e. inputs) that have no labelled output (or response)

# Matlab
![Arrays](arrays.png "Arrays")

### Matlab array indexing
- starts at 1 (not zero)
- matrix indexing is x(row,col)
    - so x(: , 3)
    - refers to all values in the third row of the matrix

### vectors indexing
- vectors only have 1 index
- because there 1D
- they're not a matrix, just an array

### Supervised learning techniques
1. Classification techniques
    - predict descrite responses
2. Regression techniques
    - predict continuous responses

# Types of classification
## Urinary classification
1. One class classifcation (OCC)
2. finds outliers
3. It's much more complex than other classification types
4. Real world examples:
    - Classification of network traffic in a secure software-defined network as normal
    - Monitoring the operational status of a neuclar power plant:  there are few examples of catastrofic issues in a power plant but many normal examples
    
## Binary classification
1. Or binomial classification
2. Classifies elements of a set into two groups
3. e.g. spam/not-spam

## Multiclass classification
1. Or multinomial classification
2. if the size of the class is 3 or more - multinomial/multiclass
3. Qualitative credit score assignment i.e. good credit, poor, excellent, exemplary

## Multilabel classification
1. similar to multiclass but have multiple labels involved
2. each training example has many lables
3. i.e. descriving an image: people, truck, vegetation and lion labels in a photo of a truck in a sahara lion tour
## Imbalanced classification
1. The number of observations in each class is unequally distributed
2. Generally can be modelled as binary classification tasks
- majority of data in training data set - belong to normal class
- minority of data in training set - abnormal class
3. Can be a slight to a severe inbalance
4. Used in fraud detection, outlier detection and medical diagnosis

# Classification Alogrithms
## Week 2 - Lecture 3

Many classification algorithms can be used to solve classification problems such as: 
 1. Urinary classification
 2. Binary classification 
 3. Multiclass classification
 4. Multilabel classification
 5. Imbalanced classification

Common algorithms are: 
1. Logistic Regression
2. Support Vector Machine
3. Discriminant Analysis
4. Naieve Bayes
5. k nearest neighbor

### Logistic Regression
- is NOT regression
- It's a classification algorithm that shares a very similiar formula to linear regression
- **Works by** using a logistic function to model a binary dependant variable i.e. binary classification
    -   more advanced formulas for multiclass classification exist
- often the start of Binary Classification
    - data can be sepearated by a single linear boundary
### SVM (Support vector Machine)
- Classification alogrithm
- Carries out classification by finding a linear decison boundary (or hyperplane)
    - that seperates all instances of one class from another
- e.g. for a 10,000 D dataset, SVM puts all feature vectors on an imaginary 10,000 D (dimention) plot and draw an imaginary line seperating the two classes
- Optimum hyperplane for SVM classifcation model is when the data is linearly seperable 

### SVM (Support vector Machine)
- for non-linear seperable data, if the hyperplane cannot seperate data in a straight line, a hinge loss function is introduced to penalise data on the wrong side of the line
- SVM classifier works well for high-dimentionality, non- lineaarly seperable data.
- typically for binary classification
- also used for multiclass classification
    - technique callled error correcting output codes (ECOC)
    - ECOC allows multiclass classificaiton to be reframed as binary classificaion
    - One vs Rest: (OvR) splits multiclass into one binary problem per class
    - One vs One (OvO) splits multiclass into one binary problem per each pair of classes


2.7: Assignment 2 - Unary Classification and Imbalanced Classification

Unary or one class classification (OCC) is used in many business cases, such as in the medical field for disease detection [1], the finance industry for credit scoring [2] and in the prediction of machine faults [3].

Similarly, to OCC, Imbalanced classification has also been used in the financial sector with credit card fraud detection possible with this methodology [4]. It has also been applied to medical situations such as by using the random forest imbalanced classification technique to find features that define heroin users [5]. In fault detection of artificial intelligence (AI), a convolutional neural network (CNN) approach to imbalanced classification has been used to predict and reduce faults in AI [6]. 

Both techniques can be helpful in classifying similar problems, the user must determine the best method for the task. Unary classification focuses on finding and identifying outliers in a training data set [7]. The large difference remains that in OCC data samples are from a single class which is known as the target class, to classify the data [8]. Whereas in imbalanced classification, there is more than one class. Usually, one class of data fits the majority, whilst the other fits to a minority class [9]. 
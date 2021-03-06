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

# Common classification algorithms are: 
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

#


## 2.7: Assignment 2 - Unary Classification and Imbalanced Classification

Unary or one class classification (OCC) is used in many business cases, such as in the medical field for disease detection [1], the finance industry for credit scoring [2] and in the prediction of machine faults [3].

Similarly, to OCC, Imbalanced classification has also been used in the financial sector with credit card fraud detection possible with this methodology [4]. It has also been applied to medical situations such as by using the random forest imbalanced classification technique to find features that define heroin users [5]. In fault detection of artificial intelligence (AI), a convolutional neural network (CNN) approach to imbalanced classification has been used to predict and reduce faults in AI [6]. 

Both techniques can be helpful in classifying similar problems, the user must determine the best method for the task. Unary classification focuses on finding and identifying outliers in a training data set [7]. The large difference remains that in OCC data samples are from a single class which is known as the target class, to classify the data [8]. Whereas in imbalanced classification, there is more than one class. Usually, one class of data fits the majority, whilst the other fits to a minority class [9]. 

Bibliography
[1] G. Cohen, M. Hilario, H. Sax, S. Hugonnet, C. Pellegrini, and A. Geissbuhler, “An application of one-class support vector machine to nosocomial infection detection,” Studies in Health Technology and Informatics, vol. 107, no. Pt 1, pp. 716–720, 2004, Accessed: May 20, 2021. [Online]. Available: https://pubmed.ncbi.nlm.nih.gov/15360906/.

[2] K. Kennedy, B. M. Namee, and S. J. Delany, “Low-Default Portfolio/One-Class Classification: A Literature Review,” Reports, Jan. 2009, Accessed: May 20, 2021. [Online]. Available: https://arrow.tudublin.ie/scschcomrep/4/.

[3] H. J. Shin, D.-H. Eom, and S.-S. Kim, “One-class support vector machines—an application in machine fault detection and classification,” Computers & Industrial Engineering, vol. 48, no. 2, pp. 395–408, Mar. 2005, doi: 10.1016/j.cie.2005.01.009.
[4] H. Zhu, G. Liu, M. Zhou, Y. Xie, A. Abusorrah, and Q. Kang, “Optimizing Weighted Extreme Learning Machines for imbalanced classification and application to credit card fraud detection,” Neurocomputing, vol. 407, pp. 50–62, Sep. 2020, doi: 10.1016/j.neucom.2020.04.078.

[5] K. Kennedy, B. M. Namee, and S. J. Delany, “Low-Default Portfolio/One-Class Classification: A Literature Review,” Reports, Jan. 2009, Accessed: May 20, 2021. [Online]. Available: https://arrow.tudublin.ie/scschcomrep/4/.
[6] A. Duan, L. Guo, H. Gao, X. Wu, and X. Dong, “Deep Focus Parallel Convolutional Neural Network for Imbalanced Classification of Machinery Fault Diagnostics,” IEEE Transactions on Instrumentation and Measurement, vol. 69, no. 11, pp. 8680–8689, Nov. 2020, doi: 10.1109/TIM.2020.2998233.

[7] A. Garcia, Learning From Imbalanced Data Sets. Springer, 2018, p. 139.

[8] M. He, J. D. Weir, T. Wu, A. Silva, D.-Y. Zhao, and W. Qian, “K Nearest Gaussian-A model fusion based framework for imbalanced classification with noisy dataset,” Artificial Intelligence Research, vol. 4, no. 2, Aug. 2015, doi: 10.5430/air.v4n2p126.

[9] Q. Leng, H. Qi, J. Miao, W. Zhu, and G. Su, “One-Class Classification with Extreme Learning Machine,” Mathematical Problems in Engineering, vol. 2015, pp. 1–11, 2015, doi: 10.1155/2015/412957.

# Week 3 Classification

## Regression in ML
- In ML regression works by building a mathematical equation or relation that defines y (the target) as a funciton of x (the predictor)

### Linear regression
- attempts to model relationship between 2 variables by fitting a linear equation to the observed data.
    - one variable is the explatory variable.
    - the other is the dependant variable
    - e.g. predicting sales data from previous months sales data to predict future months sales data.
- If the predictor variables are > 1, then it's multiple linear regression / multiple regression
    - 2 or more explanatory variables
    - financial inferance applications and econometrics

![LinearRegression](linearRegression.png "Linear regression")


### Non Linear Regression
- 2 variables
    - explanitory variable 
- describes the non-linear relationship of data
- models are generally assumed to be parametric (if the model is described as a nonlinear function)
- when data or observation has strong non-linear trend with no ease of transformation into a linear space, non-linear regression models can then be used.
    i.e. popuplation growth over time

![nonlinearRegression](nonlinearRegression.png "Linear regression")

## Regression Algorithms - Lecture 2 Week 3
Regression analysis
1. Linear Regression
2. Multiple linear regression
3. Nonlinear analysis

Common regression algorthms are: 
1. Linear Regression
2. Nonlinear Regression
3. Gaussian Process Regression
4. Suport Vector Machine (SVM) Regression
5. Generalised Linear Model
6. Decision Tree Model

Decision trees 
- can be used for classifcation and regression 
- predicted by following decisions in the tree from begging (root) to a leaf node


(5m https://wrexhamglyndwr.instructure.com/courses/741/pages/3-dot-3-lesson-2-common-regression-algorithms?module_item_id=41094)

# Week 4 Machine Learing
## Applied unsupervised Learning.
1. data that doesn't have labelled responses
    - inputs only no outputs
2. Usually Cluster analysis/clustering
3. Data particitioned into clusters
    - same cluster very similar, other clusters dissimilar

### Hard Clustersing & Soft Clustering

#### Hard Clustering
1. Each data point belongs to only one cluster
2. e.g. determine if a tweet is positive or negative
    - **k-means v popular hard unsupervised clustering algorthm**
    - k-medoids
    - Heirachrichal clustering
    - Self-Organising Map
#### Soft Clustering
1. Each data point belongs to many clusters
    - **Fuzzy c-means v common soft unsupervised learning technique**
    - Gaussian Mixture Model
## Unsupervised Learning
- Cluster analysis

## Unsupevised Learning - Hard Clustering
### K-means clustering
1. Each data point belongs to one cluster
2. Partion the data set into k number of mutually exclusive clusters
3. How well data point fits into a cluster is determined by the distance. typically - Euclidean distance.
4. Number of clusters specified a priori, beforehand
5. **k is selected by an educated guess - that's all**

#### How K-means works
1. Decide k (number of clusters)
2. Select k random points from the data as centroids
3. Compute the distance of each datapoint to each centroid.
4. Assign the nearest/closest cluster centroid to each data point
5. Calcualte centroid of newly formed cluster and assign this as the new centroid
6. Repeat steps 3 & 4.
7. This is an iterative process & keeps running until the centroids of the newly formed clusters don't change or maximum number of iterations are reached.

### K-medioids
1. Very very similar to k means but the centroid is a data point, not random point
2. Therefore there is a greater interpretability of the cluster centers than in k-means.

![kmedoids](kmedoids.png "K medoids")

#### K-medoids best used when: 
- number of clusters is known
- To scale large data sets
- for fast clustering of catagorical data

### Hierarchichal Clustering 
- Premises on k-means 
    - but dont have to predefine the number of K beforehand (clusters)
- Builds nested sets of clusters by analysing similarities between pairs of datapoints and groups objects into a binary heierarchical tree.
- It combines most similar clusters together & continues until only one cluster left

It can be performed in 3 main ways
1. Agglomerative heircical 
2. Divisive Heirarchical Clustering
    - if there are n datapoints
    - all datapoints are assigned to a single cluster.

### Heirarchical C
### Self organising map (SOM)
- transfers higher dimentions to lower dimentioins
- Neural network based clustering algorithm that transforms a dataset to 2D, it is a dimentional reduciton method.
- adoption of competive learning as opposed to error correction learning.

### Fuzzy C-means soft clustering algorithm
- fuzzy c means when # of clusters is known
- soft-clustering algo
- parition based for of clustering.

## Gaussian Mixture model
- Soft clustering algorithm
- Partition based clustering algorithm
- one multivariate normal distribution (Gaussian distribution) is used to model the probability density function.

## Reinforcement Learning
1. Dont cluster or label data
2. Find reward instead (or optimal outcome) with the use of an agent
3. Used in financial industry in trading and equity
4. Used in games - gets superhuman results sometimes
5. In the terminology, the environment is everything - except the agent (or everything that exists outside the agent).
6. The agent is a piece of software that learns from, interacts with and explores the environment
7. Environment could be
    - real
    - simulated

### The Agent in reinforcement learning
1. is a piece of software that determines
2. how to map the env & what actions to take
3. Discovers which actions yeild best results by trying them out.
4. Agent takes inputs and maps them to outputs
5. Reward helps reinforcement learning understand when the policy is getting better

![agent_reinforcementLearning](agent_reinforcementLearning.png "agent_reinforcementLearning")

### Reinforcement Algorithms
1. Work by guiding the agents exploration or exploitation of the environment
2. It's not always very obvious where to set the balance between these two.
    - generatlly should start with more exploration and move to exploitation
3. There are algorithms to help
4. Depending on the agents knowledge of the enviorment, these algorithms can be grouped as
    - model free or
    - model based
5. On- policy learning methods 
    - aim to evaluate or improve the policy that is used to make decisions 
    - example of an algorithm: Q-Learn 

6. Off-policy learning methods
    - evalualte or improve a policy different from the one that was used to generate the data.
    - example of an algorithm: SARSA (State action reward state action)

#### Q Learn
- can identify an optimal action-selection policy for any given FMDP

Policy Iteration
- policy evaluation
- policy improvment
    - keeps iterating until convergence

Value Iteration
- 
-youtube video background created
- logo created
- thumbnail to be created
- created thumbnail
- uploaded background

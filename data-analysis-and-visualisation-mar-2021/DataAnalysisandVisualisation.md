# 1.0.0: Week 1 Introduction

Weekly Introduction

    Welcome to Week 1! During this week we will cover a brief, clear and concise overview of the field of data sciences and the evolution of big data from a technical point of view. You will see how to harness the power of a large amount of data, big data and data science for new insights and information using appropriate data analysis tools and technologies. You will see why you want to use data visualization and why you might prefer to use Python and associated tools for developing your data science project or business. Then we're going to go over some simple examples of how to actually use these tools.

## DUE: Early in the week

### Read 
the following early in the week to help you respond to the discussion questions and to complete your assignment(s).

#### Required Readings:
- Ceder, N (2018) The Quick Python Book. Third Edition, Manning Publications Co, Shelter Island, Chapter One and Chapter two. (WO 3)
- The Data Science Venn Diagram (Links to an external site.) (Read later in the week) (WO 2,3)
#### Suggested readings:
- (2015) Data Science and Big Data Analytics: Discovering, Analyzing, Visualizing and Presenting Data. Wiley, Chapter one. (WO 1,2)


## 1.1: What is Data Science?
    Data Science is not about Data, Math or Statistics and surely is not about fundamentals Sciences practised in the research laboratories. This presentation provides an introduction to data science concepts and their importance. Since this module is rather hands-on and technical, you should know precisely what it is about and what it is not about. This will help you to focus your efforts in the right direction as you are required to use various tools and technologies in data science and apply them to your data effectively. We are also looking into some popular tools used in data science.

    
Read through the presentation as I explain the following topic: Toward a better and more technical understanding of Data Science, its importance and required tools

 

As you view the presentation, reflect on the following:

What is data science about and what isn’t it about?
What is the science in data science about?
Is data science a new science or new data type or just a new jargon?
Why is so important?
Why do we want to visualize data and what is its significance?

While you watch this lecture, reflect on the below questions.

    Are there any additional reason, not listed in the video, for big data systems failure?
    What might be the extended impact on an organisation of a big data system failure?
    Are there any circumstances where failure of big data may have an effect on a wide population?


## BOOK NOTES
### The Quick Python Book chapter 1
#### Types are associated with objects, not variables. 
- A variable can be assigned a value of any type, and a list can contain objects of many different types. This also means that type casting usually isn’t necessary, and your code isn’t locked into the straitjacket of predeclared types.
####  Python typically operates at a much higher level of abstraction. 
- This is partly the result of the way the language is built and partly the result of an extensive standard code library that comes with the Python distribution. A program to download a web page can be written in two or three lines!
#### Syntax rules are very simple. 
- Although becoming an expert Pythonista takes time and effort, even beginners can absorb enough Python syntax to write useful code quickly.


      Python is a very expressive language. Expressive in this context means that a single line of Python code can do more than a single line of code in most other languages. The advantages of a more expressive language are obvious: the fewer lines of code you have to write, the faster you can complete the project. Not only that, but the fewer lines of code there are, the easier the program will be to maintain and debug.

#### Indentation
- Python’s main advantage in this department is its use of indentation. Unlike most languages, Python insists that blocks of code be indented.

- Python, you should have everything you need to do real work, without the need to install additional libraries. 
- This is why the Python standard library comes with modules for handling email, web pages, databases, operating system calls, GUI development, and more.

For example, with Python, you can write a web server to share the files in a directory with just two lines of code:

      import http.server
      http.server.test(HandlerClass=http.server.SimpleHTTPRequestHandler)

      
Python is a modern, high-level language, with many features:

Dynamic typing
Simple, consistent syntax and semantics
Multiplatform
Well-planned design and evolution of features
Highly modular
Suited for both rapid development and large-scale programming
Reasonably fast and easily extended with C or C++ modules for higher speeds
Easy access to various GUI toolkits
Built-in advanced features such as persistent object storage, advanced hash tables, expandable class syntax, universal comparison functions, and so forth
Powerful included libraries such as numeric processing, image manipulation, user interfaces, web scripting, and others
Supported by a dynamic Python community
Can be integrated with a number of other languages to let you take advantage of the strengths of both while obviating their weaknesses

## IDLE Python shortcuts
        Everything in your session is buffered. You can scroll or search up, place the cursor on any line, and press Enter (creating a hard return), and that line will be copied to the bottom of the screen, where you can edit it and then send it to the interpreter by pressing the Enter key again. Or, leaving the cursor at the bottom, you can toggle up and down through the previously entered commands using Alt-P and Alt-N. This will successively bring copies of the lines to the bottom. When you have the one you want, you can again edit it and then send it to the interpreter by pressing the Enter key. You can complete Python keywords or user-defined values by pressing Alt-/.

## Python terminals
### Windows search python3
-  try pressing the up arrow key a few times. Notice how this recalls previous lines of Python code. You can use the left and right arrow keys to move backwards and forwards through a recalled line and can delete text or insert new text in the usual way.**
### IDLE 
- Try entering some Python code at the prompt to satisfy yourself that it behaves similarly to the interactive interpreter seen earlier. (One important difference is that you move through the history of previous lines using Alt+P and Alt+N instead of the up and down arrows). Now let’s edit and run the program created earlier. Choose Open... from IDLE’s File menu, or just press Ctrl+O. Navigate to your desired directory and double-click on hello.py to open it
# Week 4
![image](week4_typesOfDataandAnalytics.png)

## Correltaion
- is an analysis technique
- says if 2 things are related
- how close are they related
    - how does var a increace in correlation with var b
    - helps discover patterns and anaomolies
- if they are correlated
    - commonly used for data mining 
    - can reveal the nature of a dataset
    - aligned on a linear relationship
        - this means when one var changes so does the other one also changes, proportionally and constantly
        - expressed as a decimal between -1 and 1 - **correlation coeficent**
        - strong to weak when moving from -1 to 0, or, +1 to 0

**image**  <br/>
**- first plot shows +1 correlation, strong positive (up) correlation between 2 variables** &nbsp; <br/>
**- second plot shows 0 correlation, suggesting there is NO relationship (0) between 2 variables**  <br/>
**- third plot shows -1 correlation, suggesting there is a strong negative (down) correlation between 2 variables**
![image](week4_correclationcoefficent.png)
**image <br/> linear and non linear regression**
![image](week4_overviewOfRegressionAnalysis.png)

### correlation does not emply causation.

## clustering
- data clustered by an algorithm - 
- generally used in data mining
- differnet clusters formed for different algorithms used.
- classifcation can be used to make better desistions on clusters
- skattergraph provides visual representation of a scatter plot.
    - visually identifies outliers (image: plot 2)
- grouped using clustering
- outlier detection
    - identify differnt datasets from or incosistent from rest of dataset
    - machine learning technique to identify anomolies, abnormaliteis 
        - could identify risks or opportunites
        - closely related to clustering
        - fraud detectjon, sensor data analysis

![image](week4_OveriviewOfOutliers.png)

</br>

### Read:  

EMC. (2015) Data Science and Big Data Analytics: Discovering, Analyzing, Visualizing and Presenting Data. Wiley, Chapter three, section 3.3 to 3.3.3. (exclusive)

3.3.3 Wilcoxon Rank-Sum Test A t -test represents a parametric test in that it makes assumptions about the population distributions from which the samples are drawn. If the populations cannot be assumed or transformed to follow a normal distribution, a nonparametric test can be used. The Wilcoxon rank-sum test [15] is a nonparametric hypothesis test that checks whether two populations are identically distributed. Assuming the two populations are identically distributed, one would expect that the ordering of any sampled observations would be evenly intermixed among themselves. For example, in ordering the observations, one would not expect to see a large number of observations from one population grouped together, especially at the beginning or the end of ordering. Let the two populations again be pop1 and pop2 , with independently random samples of size n 1 and n 2 respectively. The total number of observations is then N = n 1 + n 2 . The ﬁrst step of the Wilcoxon test is to rank the set of observations from the two groups as if they came from one large group. The smallest observation receives a rank of 1, the second smallest observation receives a rank of 2, and so on with the largest observation being assigned the rank of N . Ties among the observations receive a rank equal to the average of the ranks they span. The test uses ranks instead of numerical outcomes to avoid speciﬁc assumptions about the shape of the distribution. After ranking all the observations, the assigned ranks are summed for at least one population’s sample. If the distribution of pop1 is shifted to the right of the other distribution, the rank-sum corresponding to pop1 ’s sample should be larger than the rank-sum of pop2 . The Wilcoxon rank-sum test determines the signiﬁcance of the observed rank-sums. The following R code performs the test on the same dataset used for the previous t -test. wilcox.test(x, y, conf.int = TRUE) Wilcoxon rank sum test data: x and y W = 55, p-value = 0.04903 alternative hypothesis: true location shift is not equal to 0 95 percent confidence interval: -6.2596774 -0.1240618 sample estimates: difference in location -3.417658 The wilcox.test() function ranks the observations, determines the respective rank-sums corresponding to each population’s sample, and then determines the probability of such rank-sums of such magnitude being observed assuming that the population distributions are identical. In this example, the probability is given by the p -value of 0.04903. Thus, the null hypothesis would be rejected at a 0.05 signiﬁcance level. The reader is cautioned against interpreting that one hypothesis test is clearly better than another test based solely on the examples given in this section. Because the Wilcoxon test does not assume anything about the population distribution, it is generally considered more robust than the t -test. In other words, there are fewer assumptions to violate. However, when it is reasonable to assume that the data is normally distributed, Student’s or Welch’s t -test is an appropriate hypothesis test to consider. 3.3.4 Type I and Type II Errors A hypothesis test may result in two types of errors, depending on whether the test accepts or rejects the null hypothesis. These two errors are known as type I and type II errors. ● ● A type I error is the rejection of the null hypothesis when the null hypothesis is TRUE . The probability of the type I error is denoted by the Greek letter α . A type II error is the acceptance of a null hypothesis when the null hypothesis is FALSE . The probability of the type II error is denoted by the Greek letter β . Table 3-6 lists the four possible states of a hypothesis test, including the two types of errors.
Data Science and Big Data Analytics : Discovering, Analyzing, Visualizing and Presenting Data, edited by Education Services EMC, and Education Services, EMC, John Wiley & Sons, Incorporated, 2015. ProQuest Ebook Central, http://ebookcentral.proquest.com/lib/glyndwr-ebooks/detail.action?docID=1908952.
Created from glyndwr-ebooks on 2021-03-30 11:46:38.

Data Science and Big Data Analytics : Discovering, Analyzing, Visualizing and Presenting Data, edited by Education Services EMC, and Education Services, EMC, John Wiley & Sons, Incorporated, 2015. ProQuest Ebook Central, http://ebookcentral.proquest.com/lib/glyndwr-ebooks/detail.action?docID=1908952.
Created from glyndwr-ebooks on 2021-03-30 11:44:32.
</br></br></br>
# week 4

### Read EMC. (2015) Data Science and Big Data Analytics: Discovering, Analyzing, Visualizing and Presenting Data. Wiley, Chapter six.
#### Advanced Analytical Theory and Methods: Regression
</git br></br></br></br></br>
# assignment week 4 euclidian disatance
4.10: Assignment- Implementing Clustering Algorithms 
Due Monday by 13:00 Points 15 Submitting a file upload
icon Submission - Implementing the first two epochs of a Clustering Algorithm

Based on what you have seen in previous lectures regarding seen various theories and methods for data analysis, you are going to focus on clustering in this exercise. As you have seen, In Clustering, data is divided into different groups so that the data in each group have similar properties. You have seen different measures to determine the similarities in the data properties. After developing this,  classification can be used to make better predictions about similar but new or unseen data.

 

Task
Step 1 (initialisation)

In this task, you are going to use the K-means Clustering Algorithms and Euclidean distance to cluster 8 data records in a database into 3 clusters. The data records and the distance matrix based on the Euclidean distance are given below. For simplicity, the data records were already converted to x and y coordinates of a Cartesian Coordinate system. You must implement the K-means Clustering Algorithms and show by your calculation and hand plots only for two epochs  (or two rounds ) of the K-means Clustering Algorithms. In this step, you set the scene (initialisation).

 

Data Records (data points)

A1 = (2,10),

A2 = (2,5),

A3 = (8,4),

A4 = (5,8),

A5 = (7,5),

A6 = (6,4),

A7 = (1,2),

A8 = (4,9).


The distance matrix based on the Euclidean distance is given
 

Here you are required to look at your data and try to understand them. Then suppose that the initial seeds (centres of each cluster) are located at A1, A4 and A7.

 

First, draw a 10 by 10 space and plot all the 8 data points in it. Label each data point accordingly.
Highlight the initial seeds with red in the above plot.
From the above distance matrix, decide your initial 3 clusters (i.e. the examples belonging to each cluster) and show them by drawing a closed circle around them in your plot as we did it in the class.
Step 2 (epoch 1 and 2)

In this step, you are going to implement the k-means algorithm manually. It is important to do it once by hand before starting programming. Write a step by step algorithm for the k-means algorithm with its associated flow chart and then run it for 2 epochs only. During each epoch show:

Your calculations
The centres of your current cluster shown in your plot
The new clusters are shown in your plot.
The centres of the new clusters shown in your plot.
Step 3.

Answer the following question and continue your algorithm

How many more iterations are needed to converge? Draw the final result for each epoch.

 

Guidelines
You should complete all requested tasks including calculations and plots with width concise description for this activity.

 

This assignment should be submitted no later than 13:00 UK time on Monday of next week.  

 

Please make sure that you correctly cite and reference all secondary sources used.

 

Grading
 
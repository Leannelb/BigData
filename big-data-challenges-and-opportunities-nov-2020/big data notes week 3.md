# 3.0: Week 3 Introduction

    Data is the most important raw material for any analytical system.  Previous weeks have looked at identifying and qualifying data using identifiers and metadata. The quality, value, accuracy, and effectiveness of the output are heavily dependent on the adequacy of the input data. According to George Fueschsel, and early IBM programmer and instructor, "garbage in garbage out".  Appropriate measure and standards must be implemented for data collection, identifying sample space etc. Once collected the data must be evaluated and must ensure it complies with the minimum standard so that it can be classified as a reliable input source. This week will be concentrating on the challenges associated with data collection and standardisation, data reduction, ensuring immutability and adequacy of the data objects.  

As you work through this week’s content, consider the following:

- What is a data object in Big Data Collection?
- Why data objects are important
- What is the role of standardisation and why it is important?
- What are the disadvantages of complex standards?
- What are the implications of data changes in data analytics?
- How to ensure the immortality of data in Big Data Resources?- 
- When does the data become too much data?
- How to apply data reduction?
- How to ensure the adequacy of the data?
- What are the characteristics of a good big data resource?

# 3.1.0: Lesson 1 - Big Data Integration

The importance and role of adequate data objects in Big Data Analysis are unquestionable. Even though the exponential growth of digital technology has helped us create and store huge volume of data, identifying the appropriate data source and normalise the collection is still a massive challenge.  This video will be giving a general overview of the processes that are involved in collecting and integrating data objects. The corresponding chapters in the core text will be providing more detailed information about the data collection and standardisation.

As you watch this lecture, reflect on the following:

 -   What are the different stages in Data Analysis?
 -   What is the importance of Data collection?
 -   How do you identify the data sources?
 -   Why data quality is important?

### What are the different stages in Data Analysis?
 1. Data Collection
 - collecting data from different sources
 - v important need to have right data before we start
 2. Data Cleansing
 - detecting and removing innacurate data from the data set. 
 3. Data Transformation
 - converts clean data into consistent and an acceptable layout into acceptable data using standardisation and normalisaton.
 4. statistical analysis
 - data is ready for analysis
 - statistical analysis identifies trends, patterns etc.
 - statistical analysis, algorythm and visualisation.

 ###  -   What is the importance of Data collection?
 A. Garbage in garbage out.
 - if correct data isnt used in the beggining you'll never get the right results out.

### How do you identify the data sources?
- general big data collection 
1. step 1 
- buy data from data as services companies
- collect from sources
2. Store data
- in databases for further resourses
- usually involves purchasing resorses to access data from anywhere
3. Clean up the data
- remove noisy information thats not needed
- concatinate
- merge data
4. reorganise
- reorganise after clean up
- organise and restructure data after cleaning
- add structure, sort from unstructured and semi structured and assign structure.
- tools like hadoop and HDFS
5. verify data
- choose some data and make sure it works for its intended purposes


### Why data quality is important?
- without good data starting, data wont output good results
- heavily dependant on the data collected to start.

# 3.2.0: Lesson 2 - Data Analysis

The importance of appropriate and quality data in the success of data analysis has been highlighted from the beginning of this module. A number of techniques and processes have also been discussed during this week and the previous weeks. So far we were concentrating on getting the right data. good data will have its own characteristics and can be identified using these characteristic.  However, we know the data is not static, data continue to change as we gom through various stages and processes. Sometimes incorrect data that is entered or stored could be identified and modified and could impact the outcome of the analysis and the decisions made. 

As you watch this lecture, reflect on the following:

1. What is the importance of ensuring the consistency of the data through the lifetime of the analysis? 
2. How would you decide the life span of the result?
3. Is it possible to change the data at all?
4. How would managers ensure the changes are applied, hence don't affect the outcome of the analysis, even if there is a re-analysis?
5. Why reanalysis is important? 
6. What are the steps involved in ensuring the data adequacy?
7. What are the properties of good data?

- data should be normalised and satisfy as the raw material
- data input shoud be accurate and appropriate
    - if system was created with incorrect data type can cause issues
    - errors when data is incorrectly associated with the wrong data type - human error when reading the data 
    - processing errors generating wrong output and storing the data
    - resulting in incorrect decision making
    - wider implications if these are wrong
    - must do realysis and look at the answers for comparison to make sure as expected.

- data objects are immortal and cannot be modified -> immutable
    - marrage names changing should still store maiden name.
    - changes are associated to the data instead and added to it via the metadata association.
    - changing any data makes it unverifiable 
    - modify the data without changing the original data

- data could be in assci format, need to use an appropriate editor
    - data could have readme or index files these are important for gathering data
    - size of data set is important
        - can be found my counting the number of records
        - Having realistic assumptions on the expected number of records in the data set and comparing that by the actual number sometimes might provide early warnings to the inadequacy of the data set. 
- finding data identifiers will allow integration
        - standard classification ontonology enhanses the data value
- identifying weather the data has associated meta tags
- is the data complete and representive
- by studying the data you can spot weather the data is exxecive or defficent.

### Properties associated with good data
- timestamped
- tagged with metadata
- uniquely identifiable
- data that resides within the data object
- has membership within a defined class
- data can explain itself - self descriptive
- immutable
- simplified

    7.  Plot some of the data.

Plotting data is quick, easy, and surprisingly productive. Within minutes, the data analyst can assess long-term trends, short-term and periodic trends, the general shape of data distribution and general notions of the kinds of functions that might represent the data (e.g., linear, exponential, power series). Simply knowing that the data can be expressed as a graph is immeasurably reassuring to the data analyst.

There are many excellent data visualization tools that are widely available. Without making any recommendation, I mention that graphs produced for this book were made with Matplotlib, a plotting library for the Python programming language; and Gnuplot, a graphing utility available for a variety of operating systems. Both Matplotlib and Gnuplot are open source applications that can be downloaded, at no cost, and are available at sourceforge.net. [Glossary Open source]

Gnuplot is extremely easy to use, either as stand-alone scripts containing gnuplot commands, or from the system command line. Most types of plots can be created with a single gnuplot command line. Gnuplot can fit a mathematically expressed curve to a set of data using the nonlinear least-squares Marquardt-Levenberg algorithm [1,2]. Gnuplot can also provide a set of statistical descriptors (e.g., median, mean, and standard deviation) for plotted sets of data.

Gnuplot operates from data held in tab-delimited ASCII files. Typically, data extracted from a Big Data resource is ported into a separate ASCII file, with column fields separated with a tab character, and rows separated by a newline character. In most cases, you will want to modify your raw data, readying it for plotting. Use your favorite programming language to normalize, shift, transform, covert, filter, translate, or munge your raw data, as you see fit. Export the data as a tab-delimited file, named with a .dat suffix.



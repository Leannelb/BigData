# big data notes week 2

The previous week have introduced you to the world of Big Data. You have also learned about the different V's and the significance of them in Big Data. The modern IT systems can process a large volume of data with minimum effort, however, processing variety or the varied format of data is a big stumbling block and a major challenge for big data technologies. This week will be focusing on different data objects and data types and classifying them into structured, semi-structured and non-structured. As you might have already known, the majority of data fall into the unstructured category and it becomes necessary to create identifiers to identify these unstructured data objects. Metadata and classification will also play a major role in describing, providing meaning and classifying data.

 As you work with this week's content please consider the following questions. 
 - Why is
unstructured data important? 
- Can you analyse unstructured data? Can you
provide a structure to unstructured data? 
- And if so, how would this be
done? 
- What is the role of data identification methods? 
- How do metadata
classification and ontologies help increase the value of the data? 
- And
what are the major challenges in choosing an appropriate model?

Traditionally IT systems were designed to store and process structured data where data is modelled into fields of fixed length and type ensuring the data entered into each field is constrained by a predefined set of allowed values. However, modern IT systems are designed to generate, store and process unstructured data. According to Gartner, 80%  of the enterprise data are unstructured. 

As you can imagine storing, processing and analysing structured data is relatively easy and many technologies like Structured Query Language is capable of performing these tasks.  Previous week explained you the danger of relying heavily on the structured data in decision making and failing to identify and understand the wider picture and implications. 

Big data resources are mainly unstructured.  Analysing unstructured data is a complex process. These data objects must be identified and described adding meaning to the data. 

This lesson will be concentrating on understanding the unstructured data and explore the first steps in managing unstructured data.

## 2.1.0: Lesson 1 -Structured and Unstructured Data

As you watch the lectures, reflect on the following:

    What are the different types of data?
    Why is unstructured data important?
    Can you analyse unstructured data?
    Can you provide a structure to unstructured data, if so, how?
    What is the role of data identification methods?

## 2.1.1: Structured and Unstructured Data

This video provides a brief overview and comparison of different data types as well as highlighting the complexities involved in analysing unstructured data.

Watch as I introduce you to the following topics: Structured data and applications, Semi-structured data, Unstructured data, and analysing unstructured data.

As you watch this lecture, reflect on the following:

    What are the different types of data?
    Why unstructured data is important?
    Can you analyse unstructured data?
    Is analysing unstructured data a complex process?

### What are the different types of data?
    sources include: machine generated data from sensor networks, scanning devices, machine log, aeroplane engines, consumer driven data from social media and transactional data.

### semistructured data
- doesnt hace a tabular form
- flexible and adaptable
- html, xml, CSV files, NoSQL documents

### Why unstructured data is important?
- no predefined format
- human generated
- machine data, survelence 

## new title

- no predifined format
- any type
- no constraints
- any data type
- cannot be stored in a DB
- image, video, clickstream, sensor data, log files & much more etc.

![image](/structuredAndUnstructuredData.png)
![image](/structuredAndUnstructuredDataII.png)

#### processing unstructured data
- natural language processing NLP 
- pattern matching
- clustering
- classification
- etc.

#### may have to force structure
- processiing free text
1. translate into language
2. parse into sentences
3. extract and normalise
4. mapping and annotating
5. classifying data
6. store data
7. index the data item

**read CH 3 of book**


## 2.1.2: Data Identifiers

icon Lecture - Identifying and De-identifying Data

As you have learned from eh previous lecture the majority of the data you wanted to analyse is unstructured and the process is complex and time-consuming.  The example used in the previous lecture highlighted that it is necessary to structure the unstructured data to unravel the hidden information using analytical techniques.

Structuring an unstructured data is a step by step approach using various tools and techniques. importance to provide a structure. This video will discuss the first step in data management, identifying the data objects. At the same time is also extremely important to protect the privacy and confidentiality of the individual and the data.

Watch as I introduce you to the following topics: Identifiers, data identification, de-identification and re-identification.

As you watch the lectures, reflect on the following:

    Can you provide a structure to unstructured data, if so how?
    How do you identify the data objects?
    How do you ensure anonymity?

### data identification
- links information
- identifiys data object
- ignoring correct identification will cause failures

#### de identification
- removes links

#### re-identification
- restablishes link

#### unique identifier
- distingushed from each other
- UUID - Universaily Unique Identifer
- 128 bit long identifier
- 10^18 chance of 2 of the same identifiers being assigned and clashing causing an error.

#### Bad Identifier
- name: female name, course name - may change
- Embedded information: collect confidential information (dont do it)
- remove individuality - dont link the individual
- de-identification
- avoid personal information
- protect confidentiality
- only succesfull if data is correctly identified

### data-assign
- reconnects the personal data
- uses data identifer
- entrusting third party
- uses the data identifier to connect

### data scrubbbing
- removes unwanted information
- starts after deidentification
- identify the requirement
- create exception list - list information that needs to be avoided
- create inclusion list - list items to be included after the scrubbing. Anything not on the list is deleted.
## ch3


# 2.2.0: Lesson 2 - Metadata, Classification and Ontologies

From the previous lesson, you have learned that more than 80% of the enterprise data is unstructured. Majority of the data that is handled by Big Data applications are also unstructured. To analyse unstructured data it is vital to provide some structure. Identification techniques will help to uniquely identify each object and establish the relationship between the objects. Even though data identification is the first steps in data management,  identification process alone will not provide any meaning or value to the data object. 

This lesson will be exploring how metadata, classification and ontologies and their role in enhancing the data value and meaning. Metadata can be used to describe the data and provide the context while classification and ontologies can group the data depending on the relationship.

As you watch the lectures, reflect on the following:

    What is metadata and how it is applied to describe big data resources?
    What is the significance of metadata in Big Data Analytics?
    Why do we have to group data?
    How classification and ontologies are applied in big data resources?
    What are the major challenges in modelling big data resources?


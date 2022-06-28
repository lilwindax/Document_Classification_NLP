# Document-Classification-NLP-in-Python

## Introduction 
A.I. is a rapidly advancing field of advanced computer science. Its ability to produce intelligent machines that act and behave similarly to a human has made it increasingly attractive to almost every industry. Within it, a key branch of A.I. is Natural Language Process (NLP). The field that focuses on the interaction between computers and humans using Natural Language. (Garbade, 2018) In this field, a popular problem is the classification of documents using NLP. This problem involves training models to recognize certain patterns from given data, and then being able to correctly classify them. (Muresan, n.d) This report explores this problem, the associated NLP tools and steps, code implementation, evaluation of different classifiers, and finally the results.  

## Significance
The key significance of this case study lies in the understanding of the classification problems in NLP. This is a fundamental part of understanding NLP, how it works, and finally how it can be applied to greater projects. The classification problem is a gateway into NLP, and thus understanding it is vitally important for an individual getting into this area of study. The approach taken in this case study can be further applied in many cases. 

## Aims and Objectives
Objectives and aims are key to any study or project. Without these, it is very hard to stay on track and stay motivated. The objective of our project is to develop a model of NLP for performing document analysis in the Python programming language. The aim is to achieve this by the following: Understand the problem, understand classification, apply necessary NLP steps to the data, build the model and finally evaluate the classifiers. 

## Method/Approach

### Data set explanation:
The dataset used in this project was retrieved from Kaggle. The author Sachin Sharma has produced this dataset of document classification, for open-source use. Giving the ability to use NLP skills to predict the documents in the dataset with the correct associated labels. The dataset is available in .txt format. Within the .txt there is only one column with the label at the start. The labels are from the range 1-8. (Sharma, 2020) 

### Cleaning: 
The cleaning stage is a vital step in pre-processing the data. It helps to get the dataset from the file ready for performing NLP tasks. The original dataset used for the implementation was quite far from use in training models. The first step was to separate the data into text and labels. Then the next step was to name the columns for the dataset. The final cleaning step was to remove any punctuation that may affect the results of the model. 

### Text Tokenization:
The next stage is Text Tokenization. Tokenization is a way of separating the text into smaller components called tokens. It is the most common way of processing the raw text at the token level. (Pai, 2020) Tokenization was implemented in the code using the nltk library and the word.tokenize function. A function ran through all lines of the dataset transforming text into tokens. 

### Transformation: 
The following stage involved some Transformation of the text. This is again a method used to get the text data ready for the model and to eliminate the noise. The first step was to sort the text into decreasing order, to have the word with the highest frequency at the front. Next, the words were mapped to the index. The text was then converted into a vector, which soon was vectorized using TfidVectorizer. Finally, the data was split into the training and test sets. 

### Attribute selection:
The final stage was to select the attributes. The attributes help build characteristics for the model to learn from and build on. This is an important stage for the model as it helps to outline things more clearly. 

### Description of the selection of different classifiers:
The selected classifiers for this project were: Logistic Regression, SVC, Naive Bayes, Decision Tree, KNN, and Random Forest. These classifiers were selected due to their popularity among Data scientists. Concurrently having a greater variety of classifiers means that is it easier to see the best one. After all the objective is to have the best performing model. 

### Evaluation:
After the training process, which was fairly time-consuming given the fairly large dataset. The best performing classifier was the Multinomial Naïve Bayes algorithm. This is not a surprising result as NB is often commended for its performance in text-related tasks. (Analytics India, 2020) The worst performing classifier was the K Nearest Neighbor. The reason behind this may be that KNN does not rely on prior probabilities. 

## Results
The results of the project were quite good in the sense that the model can correctly classify the documents with their labels. The mean accuracy score is 0.84 is good, though there could have been more improvements to better this score. 

## Conclusion
Document classification is a challenging but quite satisfactory problem to solve. The process used in this case study has proven to work and provide good results in the end. This has helped demonstrated the significance of this very case study. All aims and objectives were achieved. Though there are some rooms for improvement that could be taken in future research. Such as optimizing the code to give better results and approaching the data pre-processing a different way. But all in all, the results are satisfactory and the key objective of developing a model for NLP document analysis was achieved. 

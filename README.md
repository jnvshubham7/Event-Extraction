# How to Run
**Select All Run option then all program will be running**
some program takes time for training so wait some time if required 

# Runtime
2 ms ,
2:55 m ,
1:44 m ,
1:01 m




# METHODOLOGY

Extracting event information from news articles involves several steps, including data collection, text processing, and event extraction. The following is a general methodology for extracting event information from news articles:
## Data Collection
Collect the news articles from various sources and store them in a suitable format. The news articles can be collected using a csv file.

## Pre-processing
The collected data needs to be pre-processed to remove any irrelevant information or noise. This can be done using techniques like stop-word removal, tokenization.                                                              


## Named Entity Recognition (NER)
Perform Named Entity Recognition on the pre-processed data to identify and extract relevant entities like people, organizations, and locations mentioned in the news articles. This can be done using NLP libraries like spaCy or NLTK.


## Event Extraction
Use the information obtained from NER to identify the key events or actions mentioned in the news articles. This can be done using techniques like rule-based extraction.

## Event Clustering
Group similar events based on their semantic similarity, time, and location. This step helps in summarizing the events and identifying the key events.Using dbscan we have done event clustering.

## Event Classification
Classify the extracted events into different categories based on their type and relevance to the news article. This can be done using supervised or unsupervised machine learning algorithms.

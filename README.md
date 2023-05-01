# DS-4002-Case-Study
Created by: Graham Twente

## Data
One dataset is made available for this project from UVA's Miller Center. The file millerSpeeches.json contains 1,031 speeches. This dataset is not complete as some presidential speeches are missing. The most recent version of the dataset is available at this [link](https://millercenter.org/sites/default/files/corpus/presidential-speeches.json). The dataset contains the following features.

|Column Name|Definition              |Data Type      | 
|-----------|------------------------|---------------|
|Title |The title of the speech                                                   |String         |
|Date |The date the president delivered the speech                            |Datetime       |
|President     |The president who delivered the speech                                  |String       |
|Transcript     |The text of the speech                                  |String       |

## Hook
The document DS4002CS2_SpeechTopicHook 

## Rubric
The document DS4002CS2_SpeechTopicHRubric

## Materials
The materials folder contains supplemental documents to orient students to topic modeling. First, the blog post "Topic Modelling no.10's speeches" by Christopher Lovell contains an introduction to topic modeliing and an explanation of the Latent Dirichlet Allocation (LDA) technique [1]. This document also contains examples of interpreting topics and suggestions relating to relevance and lambda parameters to adjust the relatve frequency of a word in a topic.

Second, the conference proceeding, "More Efficient Topic Modelling Through a Noun Only Approach" by Fiona Martin and Mark Johnson detail the benefits of lemmatising and limiting a corpus to nouns only [2]. The study finds this method provides improved topic semantic coherence and and reduced time to generate the topic model.


## References
[1] C. Lovell, “Topic modelling no.10's speeches,” Christopher Lovell. 03-Oct-2015. https://www.christopherlovell.co.uk/blog/2015/10/03/topic-modelling-10-speeches.html. (accessed April 30, 2023).   
[2] F. Martin and M. Johnson. (2015). More efficient topic modeling through a noun only approach. Presented at. the Australasian Langauge Technology Association Worksho, Parramatta, Australia. [Online]. Available: https://aclanthology.org/U15-1013/ 



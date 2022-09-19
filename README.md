
# Abstract Classification of arXiv Dataset

CIS 545 - Final Project

## Description

The arXiv dataset consists of abstracts from various publications. Being able to predict the
most relevant categories of a random publication from the abstract might be a daunting
task to an individual if he does not have an idea of that particular domain. In this case,
our model will be able to identify the most relevant categories to which the abstract
belongs thereby helping the individual.

Our implementation will come in very handy for students involved in research work or
project work. Say, for example, they are starting their research process on a project in
Data Science and have a reference paper at hand. They could pass in the abstract to
our model and our model will predict the most relevant categories to which the paper
pertains. Using the categories predicted, they can filter out their searches and obtain
research publications that are closely related to their reference paper. This largely
simplifies the paper scouting process and helps students to find relevant papers on
which they start and proceed with their research from.
## Objectives

1. Perform an extensive study on the dataset at hand with attention to Abstracts and the broad domain of science to which the publication belongs.

2. Understand the data better using powerful visualization tools like Word Clouds, heat maps, etc.

3. Extract text pertaining to the Abstract and the corresponding domain/category to which the publication belongs in the right form and model the relationship between the two using various kinds of NLP techniques best suited for classification.

4. The ultimate objective, given the abstract of any published paper, is to predict the most (top 3 or top 5) relevant categories/domains to which the abstract of the paper would belong.
## Team Members

* [Gopik Anand](https://github.com/ganand2021) 
* [Arvind Balaji Narayan](https://github.com/narvind24/)
* [Bharathrushab Manthripragada](https://github.com/mbharath)
## Repo Content Explanation

The **Models** directory consists of independent jupyter notebooks for each model we trained for this project which can be executed as a whole as long as the data exists in the working directory.
Depending upon the amount of data used for the training set and the test set, the models are further classified into the following directories:

- *5 years*
- *10 years*

The **EDA (Exploratory Data Analysis).ipynb** jupyter notebook details the steps we took to curate and preprocess the data before training.
## Results

#### 5 Years
| *Model Name*     | *Validation Accuracy* | *F1 Score*     |
| :---            |    :----:           |          ---:|
| Naive Bayes            |  0.6040903821         |         0.6040903821|
| SVM            |    0.7527747286           |          0.7527747286|
| BiLSTM            |    0.6629           |         0.6629|
| TextCNN            |    0.6716           |         0.7009|
| BERT            |    0.7761039855           |          0.7939133476|
| Electra            |    0.5615469074           |          0.6136350938|
| Canine            |    0.6580456264           |          0.6950643406|
| GPT2            |    0.7671099183          |          0.7859698507|
| ALBERT          |    0.7325850921          |          0.7599165824|
| DistilBERT            |    0.7895571551           |         0.8013057698|
| LinkBERT            |    0.7760179048           |          0.7928416905|
| SqueezeBERT            |    0.7553360166           |          0.7800443728|
| RoBERTa            |    0.761637826           |          0.7851482741|
| DeBERTa            |    0.7838512525           |          0.7983321369|
| XLNet  |        0.7663779431       |       0.7862511261         |



#### 10 Years

| *Model Name*     | *Validation Accuracy* | *F1 Score*     |
| :---            |    :----:           |          ---:|
| Naive Bayes            |  0.6871904438         |          0.6871904438|
| SVM            |    0.7256482471           |         0.7256482471|
| BiLSTM            |    0.7081           |          0.7081|
| TextCNN            |    0.6956           |         0.7166|
| BERT            |    0.8050739587          |          0.8168410421|
| Electra            |   0.6967503765           |          0.7307768729|
| Canine            |    0.7583621425           |          0.7726365489|
| GPT2            |    0.8049861739           |          0.8165243995|
| ALBERT          |    0.7858052056           |          0.7993805028|
| DistilBERT            |   0.7945791033          |          0.8078825855|
| LinkBERT            |    0.8045033578           |          0.8162088892|
| SqueezeBERT            |    0.764803031         |          0.7871333262|
| RoBERTa            |   0.8111311065       |          0.8202364929|
| DeBERTa            |    0.8221497043           |          0.8221497043|
| XLNet  |        0.8013372824     |       0.8139960769       |


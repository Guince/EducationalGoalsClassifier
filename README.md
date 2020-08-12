# EducationalGoalsClassifier


## Description

If you want to create an individual educational trajectory, you should have a specific goal. EducationalGoalsClassifier is a classification model that determines the degree of specificity of the user's educational goals in the distance education system. The algorithm is based on a topic modelling with additive regularization. The model explicitly takes into account the assumption of splitting texts, words and topics into specific and non-specific.

It also can provide interesting diagrams "topics - specificity" and "tokens - specificity" and lists of the most characteristic tokens for each topic.

## Visuals

The degree of specificity was calculated for all documents (educational goals). The degree of specificity for a document is defined as the likelihood that it relates to any of the specific topics. The figure shows the specificity of all documents.

Specific topics: topic_3, topic_4, topic_5, topic_6, topic_7, topic_8.

Non specific topics: topic_0, topic_1, topic_2.

It can be seen that documents related to specific topics really have high specificity, and low specificity to non-specific ones.

!["topics - specificity" diagram](https://github.com/Guince/EducationalGoalsClassifier/blob/master/images/specifisity_all_documents.png)

## Usage

This is the sequence in which to use Jupyter notebooks. 

1. [Знакомство с данными.ipynb](https://github.com/Guince/EducationalGoalsClassifier/blob/master/%D0%97%D0%BD%D0%B0%D0%BA%D0%BE%D0%BC%D1%81%D1%82%D0%B2%D0%BE%20%D1%81%20%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D0%BC%D0%B8.ipynb) - Getting to know the data

2. [Предобработка и анализ исходных данных.ipynb](https://github.com/Guince/EducationalGoalsClassifier/blob/master/%D0%9F%D1%80%D0%B5%D0%B4%D0%BE%D0%B1%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%BA%D0%B0%20%D0%B8%20%D0%B0%D0%BD%D0%B0%D0%BB%D0%B8%D0%B7%20%D0%B8%D1%81%D1%85%D0%BE%D0%B4%D0%BD%D1%8B%D1%85%20%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85.ipynb) - Preprocessing and analysis of initial data

3. [Baseline. ARTM и логистическая регрессия.ipynb](https://github.com/Guince/EducationalGoalsClassifier/blob/master/Baseline.%20ARTM%20%D0%B8%20%D0%BB%D0%BE%D0%B3%D0%B8%D1%81%D1%82%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%B0%D1%8F%20%D1%80%D0%B5%D0%B3%D1%80%D0%B5%D1%81%D1%81%D0%B8%D1%8F.ipynb) - Baseline. Additive regularization topic model and logistic regression

4. Main Decision

* [Main Decision. Ф00 по D0. Подбор параметров.ipynb](https://github.com/Guince/EducationalGoalsClassifier/blob/master/Main%20Decision.%20%D0%A400%20%D0%BF%D0%BE%20D0.%20%D0%9F%D0%BE%D0%B4%D0%B1%D0%BE%D1%80%20%D0%BF%D0%B0%D1%80%D0%B0%D0%BC%D0%B5%D1%82%D1%80%D0%BE%D0%B2.ipynb) - Main Decision. Φ_00 (block of Φ matrix) is built according to non-specific documents

* [Main Decision. Ф00 случайно. Подбор параметров.ipynb](https://github.com/Guince/EducationalGoalsClassifier/blob/master/Main%20Decision.%20%D0%A400%20%D1%81%D0%BB%D1%83%D1%87%D0%B0%D0%B9%D0%BD%D0%BE.%20%D0%9F%D0%BE%D0%B4%D0%B1%D0%BE%D1%80%20%D0%BF%D0%B0%D1%80%D0%B0%D0%BC%D0%B5%D1%82%D1%80%D0%BE%D0%B2.ipynb) - Main Decision. Φ_00 (block of Φ matrix) is built randomly

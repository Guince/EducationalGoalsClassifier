# EducationalGoalsClassifier


## Description

If you want to create an individual educational trajectory, you should have a specific goal. EducationalGoalsClassifier is a classification model that determines the degree of specificity of the user's educational goals in the distance education system. The algorithm is based on a topic modelling with additive regularization. The model explicitly takes into account the assumption of splitting texts, words and topics into specific and non-specific.

It also can provide interesting diagrams "topics - specificity" and "tokens - specificity" and lists of the most characteristic tokens for each topic.

## Usage

The degree of specificity was calculated for all documents (educational goals). The degree of specificity for a document is defined as the likelihood that it relates to any of the specific topics. The figure shows the specificity of all documents. It can be seen that documents related to specific topics really have high specificity, and low specificity to non-specific ones.

!["topics - specificity" diagram](https://github.com/Guince/EducationalGoalsClassifier/blob/master/images/specifisity_all_documents.png)

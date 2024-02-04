# Semantic Textual Relatedness on Spanish using Different Models and Linguistic Features

## Authors
Saif-Ur-Rehman and Muhammad Roshail Azhar  
Department of Computer Science, Capital University Of Science & Technology, ISB, PK  
Email: bcs211119@cust.pk, bcs211130@cust.pk  
Correspondence: Ms. Mamoona Bilal, mamoona.bilal@cust.edu.pk  

## Abstract
This research focuses on Semantic Textual Relatedness (STR) in Spanish, investigating various models and linguistic features to measure semantic association between text pieces. While STR in English is extensively studied, its exploration in Spanish remains limited. This study aims to bridge this gap by evaluating STR models' performance on Spanish text and analyzing the impact of different linguistic features.

## Keywords
Natural Language Processing, semantic textual relatedness, Spanish language, machine learning, regression, transformer models.

## Introduction
Semantic Textual Relatedness (STR) plays a vital role in NLP, used in information retrieval, machine translation, and question answering. However, most research has focused on English text, leaving a gap in understanding STR in other languages like Spanish. This study evaluates and compares the performance of three STR models on Spanish text, examining linguistic features' efficacy.

## Related Work
While STR in English is extensively researched, literature on STR in Spanish is lacking. Existing studies propose approaches like machine learning and neural networks for STR in English, with limited focus on Spanish linguistic features.

## Methodology
### Dataset
The study utilizes the SemEval-2024 Spanish STS dataset, containing 1,563 labeled sentence pairs split into training, validation, and test sets.

### Models
Three STR models are employed: Random Forest Regressor, Hugging Face Sentence Transformer, and GridSearchCV-tuned Random Forest Regressor.

### Linguistic Features
Linguistic features include lexical overlap, related words, and related words of the same part of speech, analyzed for their impact on STR accuracy in Spanish.

### Evaluation
Spearman's rank correlation coefficient (SRCC) is used to evaluate model performance, assessing the monotonic relationship between predicted and ground truth relatedness scores.

## Algorithms Workings
### Random Forest Regressor
An ensemble learning algorithm predicting relatedness scores for sentence pairs in the Spanish STS dataset.

### Hugging Face Sentence Transformer
A transformer-based model capturing semantic relationships and contextual information relevant to sentence pair relatedness.

### GridSearchCV-tuned Random Forest Regressor
Hyperparameter tuning technique optimizing the Random Forest Regressor for STR on Spanish text.

## Spearman’s Rank Correlation Coefficient (SRCC)
SRCC assesses the strength and direction of the monotonic relationship between predicted and ground truth relatedness scores.

## Results and Discussion
The Hugging Face Sentence Transformer emerges as the top-performing model, leveraging transformer-based architecture to capture semantic relationships in Spanish text effectively. Additionally, lexical overlap demonstrates a strong association with relatedness scores.

## Conclusion
This research addresses a gap in STR research by evaluating various models on Spanish text, with the Hugging Face Sentence Transformer performing notably well. The study underscores the importance of lexical overlap in assessing semantic relatedness in Spanish.

## Future Work
Future research aims to explore alternative transformer-based models, incorporate additional linguistic features, and conduct a comprehensive analysis of linguistic phenomena to enhance understanding of STR in Spanish.

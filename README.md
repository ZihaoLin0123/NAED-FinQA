# NAED-FinQA
This is a repository for final project of CS 590.03 NLP course.

## Abstract

NLP solutions to numerical reasoning are critical in the domain of analysing fi- nancial documents. However, current models’ results are not satisfying because they often miss the inherent properties of numbers themselves and the influence of numbers in the text. In this paper, we propose a Number-Aware Encoder-Decoder Model (NAED) which introduces two modules to the baseline model proposed by Chen et al. (2021). First, we add a digit-to-digit encoder to measure the inherent properties of numbers themselves. Second, we implement number-aware attention to handle the influence of numbers to the input text. After adding the two modules into the FinQA baseline, we conduct experiments on the FinQA dataset to verify the effectiveness of NAED. The results with the model yield an improvement over the baseline. Our best model performed with an execution accuracy score of 0.68, and a program accuracy score of 0.67. Thus overall, we see an accuracy increase of 1.2%. Key challenges, namely training resources and multi step formulas, were also identified.

## Model
<img width="983" alt="image" src="https://user-images.githubusercontent.com/71021979/190299021-eef073db-6933-4311-822a-dbba3295391f.png">

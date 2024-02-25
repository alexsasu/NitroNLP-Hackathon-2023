# NitroNLP-Hackathon-2023

The hackathon ([link](https://www.kaggle.com/competitions/nitro-language-processing-2/)) was for a multi-class classification task, consisting of classifying texts written in Romanian, from multiple sources: social media, web articles, books; into different types of sexism: sexist direct, sexist descriptive, sexist reporting, non-sexist offensive, and non-sexist non-offensive. The metric of interest was the weighted accuracy, given that the dataset was imbalanced.

Our approaches first consisted of trying classical machine learning methods, namely: **Decision Tree**, **KNN**, **MLP**; with the **BoW** representation, and, because these didn't bring us a satisfying weighted accuracy score, we moved on to a version of **BERT** called **RoBERT**, pre-trained on a Romanian corpus, which we then fine-tuned on our dataset and applied balanced weights to it.

<details>
<summary><h4>Weighted accuracy scores of our models:</h4></summary>

![image](https://github.com/alexsasu/NitroNLP-Hackathon-2023/assets/87432371/1198f713-0cab-4946-ad95-2b3229b0242b)
</details>

Our full documentation for this competition can be consulted in the "Paper.pdf".

Contributors:
- Alexandru Rosca (https://github.com/RoscaAlexandru775/)
- Alexandru Sasu (https://github.com/alexsasu/)
- Andrei Dina (https://github.com/AndreiConstantinDina/)
- Razvan Gogu (https://github.com/gogurazvan/)

# Opinion-mining-on-sarcasm-detection
Sarcasm is a type of impression in which people speak or communicate things that are completely unrelated to what is meant by them. Sarcasm is a popular way to express one's opinions or feelings, especially on social media platforms like Twitter and Instagram. A thorough examination and comprehension of sarcastic expressions can increase the correctness of opinion mining. Opinion mining is the process of determining people's or society's views or ideas about a specific problem or event. In this paper, we aimed to present the overall structure of sarcasm determining, as well as existing methodologies, different kinds of sarcasm, problems, roadblocks, and future prospects.<br/>

In this project the main focus is to make hybrid models using the pre-existing models for detecting sarcasm. The two pre-existing models used here are support vector machine and latent semantic analysis , using these two we have made a hybrid model . The aim of the hybrid model is to increase the metrics of the model like accuracy , precision , recall , f1 score.<br/>

Below is the table which compares the metrics of individual models used here with respect to their hybrid.
## Hybrid models(SVM+LSA)
|  Accuracy  |  Precision  |  Recall  |  F1-Score  |
| ---------- | ----------- | -------- | ---------- |
|    80.7%   |    71.8%    |   68.1%  |    69.7%   |
### Result analysis
● Accuracy of Hybrid approach was the highest, giving 80.7% of correctly predicted observation<br/>
● Precision score of hybrid approach was the lowest with 71.8% of correctly predicted positive observations.<br/> 
● Recall score of hybrid approach was 68.1% . <br/>
● F1 score of Hybrid approach was the highest, presenting with 69.7% of harmonic mean  between precision and recall.<br/>     
#### Below is the Bar graph which shows the metrics of the hybrid model.
![slahybrid](https://user-images.githubusercontent.com/59058027/182412801-eeeb595a-22b3-4a86-bdbd-451dadef225c.png)
#### Below is the picture which shows the confusion matrix of the hybrid model.
![hybrid_confusion_matrixff](https://user-images.githubusercontent.com/59058027/182413087-bf4eec3c-3001-4673-addb-b8c44ec28ece.png)

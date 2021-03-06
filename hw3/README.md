# HW 3 Explanation

### Source

I used the following links for each respective Bert assignment:

- [hw_3_bert_disaster](https://www.kaggle.com/xhlulu/disaster-nlp-keras-bert-using-tfhub/notebook)
- [hw_3_bert_github_bug_feature_question](https://www.analyticsvidhya.com/blog/2020/10/simple-text-multi-classification-task-using-keras-bert/)
- [hw_3_bert_ner](https://www.depends-on-the-definition.com/named-entity-recognition-with-bert/)
- [hw_3_bert_sentiment_analysis](https://towardsdatascience.com/sentiment-analysis-in-10-minutes-with-bert-and-hugging-face-294e8a04b671)
- [hw_3_bert_spam_classification](https://www.analyticsvidhya.com/blog/2021/09/performing-email-spam-detection-using-bert-in-python/)

There was some copying and pasting and but additional code that needed to be added in order to make them work. 

Each directory has an ipynb file which shows the implementation. I took a screenshot of both the WandB and gradio and added those as well. I will showcase them below.

### Overview

Every bert example has a ipynb file with a gradio and WandB implementation. The ipynb file has comments and instructions on how it works. 

The `hw_3_bert_ner` is the only example with a custom WandB implementation since we use PyTorch in that example. The Keras examples have a really nice callback function which can automatically report/record metrics. 

Also please note, some of the metrics show only one dot. This is because the training was taking very long. So I only ran for one epoch. 

### [hw_3_bert_disaster](https://github.com/wasaequreshi/CMPE-297-ET/blob/master/hw3/hw_3_bert_disaster/hw_3_bert_disaster.ipynb)

#### hw_3_bert_disaster - WandB

![hw_3_bert_disaster - WandDB](./hw_3_bert_disaster/hw_3_bert_disaster_wandb.png)

#### hw_3_bert_disaster - Gradio

![hw_3_bert_disaster - Gradio](./hw_3_bert_disaster/hw_3_bert_disaster_gradio.png)

### [hw_3_bert_github_bug_feature_question](https://github.com/wasaequreshi/CMPE-297-ET/blob/master/hw3/hw_3_bert_github_bug_feature_question/hw_3_bert_github_bug_feature_question.ipynb)

#### hw_3_bert_github_bug_feature_question - WandB

![hw_3_bert_github_bug_feature_question - WandDB](./hw_3_bert_github_bug_feature_question/hw_3_bert_github_bug_feature_question_wandb.png)

#### hw_3_bert_github_bug_feature_question - Gradio

![hw_3_bert_github_bug_feature_question - Gradio](./hw_3_bert_github_bug_feature_question/hw_3_bert_github_bug_feature_question_gradio.png)

### [hw_3_bert_ner](https://github.com/wasaequreshi/CMPE-297-ET/blob/master/hw3/hw_3_bert_ner/hw_3_bert_ner.ipynb)

#### hw_3_bert_ner - WandB

![hw_3_bert_ner - WandDB](./hw_3_bert_ner/hw_3_bert_ner_wandb.png)

#### hw_3_bert_ner - Gradio

![hw_3_bert_ner - Gradio](./hw_3_bert_ner/hw_3_bert_ner_gradio.png)

### [hw_3_bert_sentiment_analysis](https://github.com/wasaequreshi/CMPE-297-ET/blob/master/hw3/hw_3_bert_sentiment_analysis/hw_3_bert_sentiment_analysis.ipynb)

#### hw_3_bert_sentiment_analysis - WandB

![hw_3_bert_sentiment_analysis - WandDB](./hw_3_bert_sentiment_analysis/hw_3_bert_sentiment_analysis_wandb.png)

#### hw_3_bert_sentiment_analysis - Gradio

![hw_3_bert_sentiment_analysis - Gradio](./hw_3_bert_sentiment_analysis/hw_3_bert_sentiment_analysis_gradio.png)

### [hw_3_bert_spam_classification](https://github.com/wasaequreshi/CMPE-297-ET/blob/master/hw3/hw_3_bert_spam_classification/hw_3_bert_spam_classification.ipynb)

#### hw_3_bert_spam_classification - WandB

![hw_3_bert_spam_classification - WandDB](./hw_3_bert_spam_classification/hw_3_bert_spam_classification_wandb.png)

#### hw_3_bert_spam_classification - Gradio

![hw_3_bert_spam_classification - Gradio](./hw_3_bert_spam_classification/hw_3_bert_spam_classification_gradio.png)

### Demo

Please take a look at the ipynb files. Additionally please look at the images as well :)
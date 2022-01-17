# Multi Modal Approach for Sentiment Analysis

This project uses shallow machine learning models with feature engineering to predict sentiment and emotion of multi-party conversations in the TV show F.R.I.E.N.D.S. Additionally, recurrent deep learning models are used to compare and benchmark accuracy and F1 score.

## Data

Multimodal Emotion Lines Dataset (MELD) is used comprising 13708 utterances from 1433 dialogues from the TV series F.R.I.E.N.D.S. There are 7 unique emotions for each utterance, namely - Anger, Fear, Disgust, Joy, Neutral, Sadness and Surprise. There are also 3 unique sentiments - Positive, Neutral and Negative. The data distribution is as follows.

![image](https://user-images.githubusercontent.com/68541043/149840962-97870f7d-bd29-498e-99b6-cc0c9fd75641.png)

## Results

1) Using text form of dialogues, the following image depicts emotion and sentiment accuracies.

<img width="338" alt="inputdata3" src="https://user-images.githubusercontent.com/68541043/149841678-09df677a-3c6b-48f4-a5ed-68e1cd80844b.png">

2) Using audio form of dialogues, the following image depicts emotion and sentiment accuracies.

<img width="329" alt="Audiodata2" src="https://user-images.githubusercontent.com/68541043/149841714-a843ace5-ffca-47b9-a50e-33a40f2e9bbc.png">

3) Using multi-modal approach, the following image depicts emotion and sentiment accuracies.

<img width="343" alt="combinedgraph1" src="https://user-images.githubusercontent.com/68541043/149841759-99348ede-7e77-4000-821d-d293a3293bd5.png">

4) Using deep learning,

![image](https://user-images.githubusercontent.com/68541043/149841841-5c941300-0c49-4ad0-8153-9a35a885f9c6.png)

## Usage

In code folder - 
NLP_Text_final.ipynb - Using raw text data, applying feature engineering and calculating metrics using shallow machine learning models.
NLP_Text_Glove_final.ipynb - Using glove vectors from raw text data and calculating metrics using shallow machine learning models.
NLP_Audio_final.ipynb - Using raw audio data, applying feature engineering and calculating metrics using shallow machine learning models.
NLP_Audio_text_final.ipynb - Combining raw audio and text data, applying feature engineering and calculating metrics using shallow machine learning models.
NLP_Audio_text_final_6373.ipynb - Testing different feature engineering methods in multi-modal approach.
MLAI_BiLSTManswer.ipynb - Using BiLSTM with the audio features to predict sentiment and emotion.
Grapgs.ipynb - Generating graphs shown in the report.

#### For more details refer to the report - ML_Final_Report_Emotional_ASTAR.pdf





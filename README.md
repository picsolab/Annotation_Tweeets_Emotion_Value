# Annotation Tweeets - Emotion & Moral Value
Human annotation for gun relevant tweets

The dataset released here is the results of a human annotation effort to identify the emotion and moral value conveyed in tweets relevant to gun issues in the US. There was a total of 3100 tweets being annotated. These tweets were selected from a [larger dataset we constructed](https://github.com/picsolab/TRIBAL-release) that tracked two groups of Twitter users who were identified in our prior work as either Trump or Clinton supporters in the US 2016 presidential eleciton. We used this distinction as the proxy of ideology difference, considering those tweets composed from Trump supporters as messages from the Conservative camp (Con), and those from Clinton supporters the Liberal camp (Lib). Using keyword methods, we selected all tweets relevant to gun issues from the larger dataset. Among the selected 3100 gun relevant tweets, there are 1322 from Con and 1778 from Lib.

In this released dataset, there are four files.

1. [Codebook_for_emotion_Valence](Codebook_Emotion_Dominance.pdf)
This document details the inclusion criteria, training instruction for coders, and training modules implimented on Mturk.

2. [Codebook_for_emotion_Dominance](Codebook_Emotion_Dominance.pdf)
This document details the inclusion criteria, training instruction for coders, and training modules implimented on Mturk.

3. Codebook_for_MoralValue
This document details the operationalized definitions we develop and use to annotate the 10 dimensions of moral values based on Moral Foundation Theory (https://moralfoundations.org/)

4. Annotation results: Gun_tweets_emotion_value.csv
This file has 14 columns: TweetID, Ideology camp, 2 emotion annoatations, and 10 moral value annotations.

* "TweetID"
* "Group" (Con or Lib): ideology camp that the Twitter author of the tweet was labled - Con (conservative) or Lib (Liberal)
* "Valence" (-1 to 1): How positive/negative the emotion is felt from the tweet - the values range from -1 to 1; the higher the value, the more positive the tweet is felt.
* "Dominance" (-1 to 1): How much the tweet indicates a sense of Feeling-in-control - the values range from -1 to 1; the higher the value, the more feeling in control
* "Care_virtue"(0 or 1): 0 or 1 indicates whether the tweets incoporate moral judgement along this moral dimension
* "Care_vice"(0 or 1): 0 or 1 indicates whether the tweets incoporate moral judgement along this moral dimension
* "Fairness_virtue" (0 or 1): 0 or 1 indicates whether the tweets incoporate moral judgement along this moral dimension
* "Fairness_vice" (0 or 1): 0 or 1 indicates whether the tweets incoporate moral judgement along this moral dimension
* "Loyalty_virtue" (0 or 1): 0 or 1 indicates whether the tweets incoporate moral judgement along this moral dimension
* "Loyalty_vice" (0 or 1): 0 or 1 indicates whether the tweets incoporate moral judgement along this moral dimension
* "Authority_virtue" (0 or 1): 0 or 1 indicates whether the tweets incoporate moral judgement along this moral dimension
* "Authority_vice" (0 or 1): 0 or 1 indicates whether the tweets incoporate moral judgement along this moral dimension
* "Purity_virtue" (0 or 1): 0 or 1 indicates whether the tweets incoporate moral judgement along this moral dimension
* "Purity_vice" (0 or 1): 0 or 1 indicates whether the tweets incoporate moral judgement along this moral dimension

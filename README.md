# Covid-19-Sentiment-Analysis
This data is used for Global Student Competition of Covid-19 Sentiment Analysis, which is a multi-label text classification task.

Data collection: The dataset was collected by, an open source Twitter crawler, called Twint, where query words like covid-19, coronavirus, covid, corona, ect. are used. The user-related information is removed when the data are saved.

Data annoation: 11 labels and their covered auxiliary emotions are optimistic (representing hopeful, proud, trusting), thankful for the efforts to combat the virus, empathetic (including praying), pessimistic (hopeless), anxious (scared, fearful), sad, annoyed (angry), denial towards conspiracy theories, surprise (unprecedented), official report, and joking (ironical). The IRA and Kappa coefficient are 0.904 and 0.381, respectively.

Data information: There are total 10K labeled English tweets about Covid-19. The data are splitted into 5K, 2.5K, 2.5K as training data, testing data, validation data with the ratio 0.5:0.25:0.25. The training data and validation data have 13 columns, containing Tweet ID, Tweet text, Optimistic, Thankful, Empathetic, Pessimistic, Anxious, Sad, Annoyed, Denial, Surprise, Official report, Joking while testing data have two columns, Tweet ID and Tweet text. The ID information is masked to protect the user privacy.

# Data Usage Agreement
This dataset complies with Twitter’s Terms of Service. If you use this dataset, this means that you agree with the license and term of Twitter. This dataset is only used for non-commercial research.





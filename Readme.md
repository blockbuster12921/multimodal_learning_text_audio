# Multimodal learning for Audio and Text sentiment Analysis

## Requirements:

1) in the dataframe .csv file there is a column called 'session_number', from 1 to 5, these number you should use it when splitting the data into fold (5-fold-validation). for example in fold 1 training should be on session 1 to 4 and testing on session 5. And for fold 2training should be from session 2 to 5 and testing on 1 and etc.
2) please use keras only
3) if you segments the audio file you should use majority vote to get the final prediction for each audio file.
4) when making the multimodal model, it should be parameter sharing so that two LSTM layers should learn at the same time. not only catenating the embedding and get one prediction.
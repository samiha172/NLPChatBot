# NLPChatBot


We trained the Deep NLP dataset with the Sequential model at first. The dataset
contains two csv files; one contains 80 user responses and the other contains 125
resumes. By using this data, our bot determines if the user needs immediate help or
they can just keep on chatting with the bot. From the Sequential model we got an
accuracy score of 0.7256. Later we added an LSTM layer and got an overfitting score.
By adding Dropout, we finally got a score of 0.7134.

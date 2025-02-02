# Character Level Model

We attempt to generate lines of codes with a simple RNN (using LSTM cells). We won't make use of modern technique like "attention mechanisms" but we'd rather
focus on a simple model which can already show some remarkable results. We will train our network on the 'openpyxl' librairy. This model is character level, which means 
the network predicts the next characater from the past sequence.
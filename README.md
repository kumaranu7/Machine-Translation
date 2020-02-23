# Machine-Translation

Converting english texts to german text.
Process undergone:
1. Data cleaning (preserving the accent), cleaning pairs, handling unicode, 
2. Dumping the cleaned file and loading it afterwards whenever needed.
3. Splitting the 150000 examples into training and test data.
4. Defining the functions for loading the data, padding, encoding and decoding the data
5. Modeling the cleaned data (Used RNN - LSTM and Time Distributed layer), Optimizing the cost
6. Evaluating model, decoding index, predicting sequence, Bleu score

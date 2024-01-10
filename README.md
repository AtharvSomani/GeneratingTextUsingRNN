# GeneratingTextUsingRNN
We have Use in built tensorflow shakespeare file for training the model 
link is  -  'https://storage.googleapis.com/download.tensorflow.org/data/shakespeare.txt'
We have not train the model on all the data which is there in txt file, we have process total 500,000  character from 300,000 to 800,000.
We have created two dict 
1) for Char to index
2) for index to char
Then define how long a sequence shall (40) be and also how many characters(3) we will step further to start the next sentence.
Then we created a model
LSTM layer with 128 neurons, activation - softtmax
then we compile and train the model.

# Detect News Topic
## Project description
This project aims to classify news topics, based on the news content, into four different categories:    
0: Politics  
1: Sports  
2: Economy  
3: Tech  
### Train and Test data
The train data includes 12000 actual news titles and their description followed by a label of 0-3.  
The test data consists of 7600 news articles and their description without label (the reason is, this was done as part of a interview problem, therefore no label was given for test data to avoid fitting the model to the test data).
### Method
The notebook is pretty self explanatory, however, since the data was categorical, Keras's tokenization was used. Also, the deep learning model was a Keras sequenctial model.  
### Results
Results need more work. This was done in two hours. However, even with this amount of work, 90% accuracy was achieved in training and validation.

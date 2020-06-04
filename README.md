# Sentence-Boundary-Detection

For our IST 664 coursework, we developed a *Deep Learning Algorithm* for Sentence Boundary Detection problem. We made use of Data Architecture for our *CBHG model* to decide the beginning and endpoints of a sentence.

Sentence Boundary Detection (SBD), also known as sentence tokenization, is a problem in Natural Language Processing (NLP) of deciding the begin and endpoints of a sentence. Sentence boundary identification is often challenging. For example, punctuation marks can often become ambiguous while identifying.

**Dataset:** We have used Brown Corpus for our data which we have obtained using *NLTK*. The corpus contains 500 samples of English language text, totaling around *One Million words*. It is compiled from works published in the United States in 1961. 

**Python Libraries:** *Tensorflow, Tensorboard, Numpy, NLTK*

We have made use of the Modified CBHG model, which was introduced first in the research paper called *Tocatron: Towards End-to-End Speech Synthesis*. It consists of a reasonable number of hyperparameters and is a very powerful architecture. 

**Deep Learning Models:**
1. Artificial Neural Networks (ANN)
2. Convolutional Neural Networks (CNN)
3. Recurrent Neural Networks (RNN)
4. Long Short Term Memory (LSTM)

**Hyperparameter Used for training our model:**
1. Learning Rate 
2. Maximum and Minimum Number of Characters in a Sentence
3. Hidden Unit 
4. Number of Encoders and Decoders blocks 
5. Number of Head 
6. Dropout Rate 
7. Encoder Number of Bank 
8. Number of Highway Network Blocks 
9. Number of Epochs and Size of Batches. 

Here, we have used multiple deep learning models for the comparison and development of our CBHG model. We have used models like *Convolutional Neural Network (CNN), Multilayer Perceptrons (ANN), Recurrent Neural Network (RNN), and Long Short Term Memory (LSTM)*. We implemented all these models on our data and later compared it with our CBHG model based on *Accuracy* and *Size of the data*. 

We trained our model using the Training Graph which depicts the *ePoch value* against the *Training Loss time*. We also made use of the Validation Accuracy graph showing the accuracy of the model when implemented on validation data. It depicted the ePoch value against Validation Accuracy. 

Conclusion: The final accuracy obtained was **98.57%** for the CBHG model. CBHG Model gives us approximately the same accuracy when compared to other models like LSTM, BI-LSTM, and CNN.

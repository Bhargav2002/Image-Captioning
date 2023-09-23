# Image-Captioning
Implementing an encoder-decoder model that will give the text representation of the given image.

#Encoder: CNN
I used DenseNet201 model to extract the features of the image so I needed the model upto the pooling part instead of the last layer, Since the DenseNet201 model is cretaed fpr classifications purposes.
#Decoder: LSTM
LSTMs are used for the text generation process. The image embeddings are concatenated with the word embeddings and passed to the LSTM to generate the next word

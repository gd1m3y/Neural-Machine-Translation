# Neural Machine Translation 

This project focuses on Solving Sequence-to-Sequence problem of Machine translation which is conversion of English words into corresponding Hindi words by the means of a Encoder-Decoder Architecture.

# Work Flow

![image](https://github.com/gd1m3y/Neural-Machine-Translation/blob/master/NMT.png)

The work flow is as follows - 
* Preprocessing  - The inputs are converted into suitable format along with a  start and end token so that it can be fed to the encoder.
* Encoder - This is the initial part of the Encoder decoder structure where the networks learn to predict the initial texts and weights are updated.
* Decoder - This part translates the encoded weights into the target language by utilizing the weights provided by the encoder structure.

## Encoder Decoder Model
The encoder-decoder model is a way of using recurrent neural networks for sequence-to-sequence prediction problems.
The approach involves two recurrent neural networks, one to encode the input sequence, called the encoder, and a second to decode the encoded input sequence into the target sequence called the decoder.
![img](https://github.com/gd1m3y/Neural-Machine-Translation/blob/master/1_1JcHGUU7rFgtXC_mydUA_Q.jpeg)

## Dataset Used
The Dataset used is englishHindicorpora-
https://www.kaggle.com/aiswaryaramachandran/hindienglish-corpora
Which Consists of Pairs of hindi and English sentences.
## Tech Stack
* Numpy - To perform Scientific mathetatics 
* Tensorflow 2.x - A deep learning library 
* Pandas - For manipulating data

## To dos
* Improve model performance by using more training examples 
* Implement Attention mechanism for better performance
* Using Pretrained vectors for better results

## Contact
want to contribute ? contact me at Narayanamay123@gmail.com




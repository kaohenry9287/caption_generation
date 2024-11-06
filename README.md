# Project Goal: caption_generation outcome comparing
Develop an Image Caption Generator that automatically generates descriptive captions for images by combining the visual understanding of CNN with the sequence modeling capability of RNN, also compare the outcome of using RNNs (LSTM/GRU) and more advance  LLM method(BLIP) to see the dirrerent.


## 1. Step to achieve outcome
### - Image Feature Extraction: CNN (Inception V3)
Efficiently captures complex patterns in images using several types of convolutions with different kernel sizes.
The InceptionV3 model is typically used without the fully connected  layer. The output from one of the later layers is used as a fixed-dimensional vector (image feature) representing the image's content.

### - Caption Generation: RNNs (LSTM or GRU layers to generate text)
LSTM (Long Short-Term Memory): Designed to handle long-term dependencies, useful in generating coherent sentences by remembering contextual information.
GRU (Gated Recurrent Unit): A simpler, faster alternative to LSTM, which often performs similarly while being computationally efficient.

### - Alternate Model: BLIP (Bootstrapping Language-Image Pretraining)
More advanced vision-language pre-training approach



## 2. This project involve following techniques:

- CNN:  for visual feature extraction
- RNNs (LSTM/GRU): for sequential language generation
- LLM(BLIP):To compare the result.



## 3. Data Source: Flickr_8K



## 4. Data Preparation:
- Training & Validation Set：80%
- Test Set: 20%



## 5. Outcome: 

- Loss about RNN 
![截圖 2024-11-06 下午3 39 34](https://github.com/user-attachments/assets/d50c0fc8-a14a-4fe8-82e9-148bb21a5996)

- Overall outcome
![截圖 2024-11-06 下午3 40 03](https://github.com/user-attachments/assets/53b87c8a-5fca-47bf-b641-5749fa9ef355)

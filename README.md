# Automatic-Image-Captioning

This repository consists of code for automatic image captioning. The Flickr8k dataset has been used for this purpose. A hybrid CNN-LSTM architecture was considered. The RESNET-50 CNN model weights have been used to generate useful image vector embeddings which are then connected to LSTM decoder. Each image has five captions and around 32000 samples have been used for training and 8000 for testing. The models have been evaluated using BLEU score. A BLEU score of 0.18 has been obtained.

The next task that will be done is to replace the LSTM-based decoder with a transformer. The transformer is expected to perform better. The transformer will be implemented next.

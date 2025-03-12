# Action-Recognition-using-ViT
This repository contains on how to recognise actions given in a video by training it on custom video data on a pretrained ViT.

Here I have used facebook [TimeSformer: Is Space-Time Attention All You Need for Video Understanding?](https://arxiv.org/abs/2102.05095)

Link for understanding how to use from [hugging face](https://huggingface.co/facebook/timesformer-base-finetuned-k400)

The dataset used in this to train the model consists of 25 actions with 50 videos per category, in total 1250 videos. The code to process the data and convert images to videos to train the model is in the notebook file.

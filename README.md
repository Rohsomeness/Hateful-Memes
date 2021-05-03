# The Surprising Power of CLIP in the Hateful Memes Challenge
Collection of deep learning techniques used to evaluate whether a meme is hateful or not. Completed as part of Facebook's Hateful Memes Challenge and as final project for CS 4803 - Deep Learning

Abstract:
We  present  a  study  on  the  applications  of  multimodalmodels to the task of classifying hate speech within visualand textual media by training models on Facebook’s HatefulMemes Challenge dataset.  We recreate benchmarks set byboth state-of-the-art unimodal and multimodal models.  Wefind these models’ performance to be inline with the per-formance achieved by the original Facebook research team.We further explored the usefulness of CLIP, OpenAI’s lat-est multimodal model, which utilizes self-supervised train-ing on large quantities of unlabeled internet data. By train-ing and testing multiple CLIP based models, we study thebest utilization of CLIP’s image and text features. Our bestperforming model used a pre-trained CLIP model followedby a simple neural network and finetuned on a preprocessedversion of the dataset with text removed from all of the im-ages. We make a series of intriguing observations from thisstudy,  e.g,  models  using  CLIP  alone  perform  better  thanmodels which pair CLIP with another state-of-the-art textmodel such as RoBERTa. Additionally, it is notable that thebest performing CLIP model outperforms all benchmarksset out in the original Facebook paper.

Competition details here: https://ai.facebook.com/tools/hatefulmemes

Our Results:
![Results](https://github.com/Rohsomeness/Hateful-Memes/blob/main/Results.png?raw=true)

Compared to baselines from original paper:
![Baselines from original paper](https://github.com/Rohsomeness/Hateful-Memes/blob/main/Baseline.png?raw=true)

Please try out our models:

Model                                            |                                      Colab Link
| ---------------------------------------------- | -------------------------------------------- |
Naive CLIP Model + CLIP Embedding tool: | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Rohsomeness/Hateful-Memes/blob/main/models/multimodal/NaiveCLIPandEmbedder.ipynb)
Neural Network CLIP Model: Link to Naive CLIP Model + CLIP Embedding tool: | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Rohsomeness/Hateful-Memes/blob/main/models/multimodal/CLIPNeuralNetwork.ipynb)

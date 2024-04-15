# Lipreading
In this project, I have created a model that is able to infer sentences from muted video input. The model is trained on a subset of the GRID dataset, which contains videos of people speaking and the corresponding text.

## Possible Applications of this Project
The results of this can be used as 
- an education tool to analyze if foreign language speakers are using correct mouth shapes to produce the correct sounds.
- a practice tool for people with speech impairments to help them improve their speech.
- an assistance in captioning videos with poor audio quality.
- a help for people with hearing impairments who are practice thier lip reading skills.

## Inspiration
This project is inspired by the paper "LipNet: End-to-End Sentence-level Lipreading" by Yannis M. Assael, Brendan Shillingford, Shimon Whiteson, and Nando de Freitas. The paper can be found at https://arxiv.org/abs/1611.01599.

In addition, I am planning on drawing inspiration from the "Visual Speech Recognition for Multiple Languages in the Wild" paper by Pingchuan Ma, Stavros Petridis and Maja Pantic which can be found at https://arxiv.org/pdf/2202.13084v2.pdf. This paper is more recent, and uses a CTC/Attention based model to achieve state of the art results (which is what I am aiming for). I would be planning on implementing their AVSR model in this project. This will be part of a future project, as I do not currently possess adequate processing power.
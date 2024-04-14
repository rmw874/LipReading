# Lipreading
This project is an attempt to create a model that is able to lipread from a video input. The model will be trained on the GRID dataset, which contains videos of people speaking and the corresponding text. The model will be trained to predict the text from the video input.

## Possible Applications of this Project
- The results of this can be used as an education tool to analyze if foreign language speakers are using correct mouth shapes to produce the correct sounds.
- It can also become a practice tool for people with speech impairments to help them improve their speech.
- It can be used to assist in captioning videos with poor audio quality.
- Can be used to help people with hearing impairments practice thier lipreading skills.

## Inspiration
This project is inspired by the paper "LipNet: End-to-End Sentence-level Lipreading" by Yannis M. Assael, Brendan Shillingford, Shimon Whiteson, and Nando de Freitas. The paper can be found at https://arxiv.org/abs/1611.01599.

In addition, I am planning on drawing inspiration from the "Visual Speech Recognition for Multiple Languages in the Wild" paper by Pingchuan Ma, Stavros Petridis and Maja Pantic which can be found at https://arxiv.org/pdf/2202.13084v2.pdf. This paper is more recent, and uses a CTC/Attention based model to achieve state of the art results (which is what I am aiming for). I would be planning on implementing their AVSR model in this project.
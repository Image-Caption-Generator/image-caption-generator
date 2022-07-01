**Image Caption Generator**

Objective is to build a system that views an image and automatically describes the content of it in English and the description is converted to speech. 

**Introduction**
Automatically describing the content of images using natural language is a fundamental and challenging task. It is a relatively new task to let a computer describe an
image that is forwarded to it in the form of a human-like sentence. So, to make our image caption generator model, we will be merging CNN-RNN architectures. Feature extraction from images is done using CNN. We have used the pre-trained model Exception. The information received from CNN is then used by LSTM for generating a description of the image. However, sentences that are generated using these approaches are usually generic descriptions of the visual content. The captions generated are converted to speech.




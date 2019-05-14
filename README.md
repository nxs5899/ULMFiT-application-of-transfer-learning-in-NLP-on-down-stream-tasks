# ULMFiT-application-of-transfer-learning-in-NLP-on-down-stream-tasks

Transfer Leraning is changing the game. ImageNet’s impact on the course of machine learning research can hardly be overstated. The dataset was originally published in 2009 and quickly evolved into the ImageNet Large Scale Visual Recognition Challenge (ILSVRC). In 2012, the deep neural network submitted by Alex Krizhevsky, Ilya Sutskever, and Geoffrey Hinton performed 41% better than the next best competitor, demonstrating that deep learning was a viable strategy for machine learning and arguably triggering the explosion of deep learning in ML research. ( Source).

the same approach can be applied in NLP. Howard and Ruder (authors of the paper: Universal Language Model Fine-tuning for Text Classification) propose a bi-LSTM model that is trained on a general language modeling (LM) task and then fine tuned on text classification. This would, in principle, perform well because the model would be able to use its knowledge of the semantics of language acquired from the generative pre-training. Ideally, this transfer can be done from any source task S to a target task T. The authors use LM as the source task because (Source):

    it is able to capture long-term dependencies in language
    it effectively incorporates hierarchical relations
    it can help the model learn sentiments
    large data corpus is easily available for LM

this colab notebook shows how to apply transfer learning in NLP to a down stream task (sentiment analysis of Airline Tweets). please see the notebook for more details.

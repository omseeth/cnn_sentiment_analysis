## How to use a Convolutional Neural Network (CNN) for text classification (sentiment analysis) with PyTorch

This tutorial is an introduction to **Convolutional Neural Networks** (CNNs) for **sentiment analysis** with PyTorch. There are already a few tutorials and solutions for this task by [Gal Hever](https://galhever.medium.com/sentiment-analysis-with-pytorch-part-3-cnn-model-7bb30712abd7), [Jason Brownlee](https://machinelearningmastery.com/develop-word-embedding-model-predicting-movie-review-sentiment/), or [Ben Trevett](https://github.com/bentrevett/pytorch-sentiment-analysis/blob/main/3%20-%20Convolutional%20Neural%20Networks.ipynb). However, they are either written in Keras or lack some explanations that I find essential for understanding the underlying mechanics of CNNs as well as their PyTorch specific implementations. I hope this tutorial will therefore help the interested reader to learn more about CNNs and how to implement them for NLP tasks, such as sentiment analysis.

What follows is partially the result of a lecture given by [Barbara Plank](https://bplank.github.io/) at LMU in 2024, whom I'd like to thank along with her lab [MaiNLP](https://mainlp.github.io/) for letting me use some of their code. The theoretical part discussed in this tutorial is also highly indebted to [Raschka et al. (2022)](https://github.com/rasbt/machine-learning-book), whose book on machine learning is for me one of the best resources.

Check out `sentiment_analyser.ipynb` for the the following chapters:

+ **Preliminaries** imports
+ **Section 1)** Preprocessing the dataset
+ **Section 2)** Theoretical foundations of CNNs for classification
+ **Section 3)** Implementing a CNN with PyTorch
+ **Section 4)** Evaluation of results
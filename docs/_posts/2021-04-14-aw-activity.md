---
layout: post
title: AW activity
category: work
---

Recent after work activity is to implement a 2-layer neural network with the help of numpy library and [CIFAR-10 dataset](https://www.cs.toronto.edu/~kriz/cifar.html). Two things impressed me quite a lot, the first is how efficient the numpy library is in matrix calculation(multiplication especially) comparing a naive solution in c; another is the amazing deep learning, with several epoches of mini-batch GD on the network, finally I can get 61.2% accuracy on the training data and 51.6% on the test data. I also trained a single layer network before this but got less accuracy, the interesting thing is that after drawing the trained parameters I got the following picture, I feel I can roughly see what it should be given that I know the category of the dataset.. really interesting!

![Parameters image](https://github.com/ao-song/ao-song.github.io/blob/gh-pages/docs/_posts/img/w.png?raw=true)

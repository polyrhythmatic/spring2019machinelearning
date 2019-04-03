---
layout: default
permalink: /classes
title: CLASSES
---

## 4/1 - Class 5

A guest presentation from [Rebecca Ricks](https://beccaricks.space/) - a technologist, writer, and artist thinking about privacy and computational systems. Rebecca was a Ford-Mozilla open web fellow at Human Rights Watch, an organization that investigates and reports on abuses happening in all corners of the world and is now a researcher at the Mozilla Foundation. Her work interrogates the ways social platforms collect and monetize data about their users. Rebecca received her masters at NYU's ITP program and holds a B.A. in Middle East Studies/Arabic.

## 3/18 - Class 4

Class notes:

Pose Estimation is a general problem in Computer Vision where we detect the position and orientation of an object. This usually means detecting keypoint locations that describe the object. ([Source](https://www.learnopencv.com/deep-learning-based-human-pose-estimation-using-opencv-cpp-python/
))

Some examples:
* [DensePose](http://densepose.org/)
* [Body Synth](https://experiments.withgoogle.com/body-synth)
* [Move Mirror](https://experiments.withgoogle.com/collection/ai/move-mirror/view)

Pose estimation can be done for single or multiple people.

We can track face position, body position, and even use KNN classification to classify body positions - [code](https://github.com/channelstudio/spring2019machinelearning-code/tree/master/wk04_posenet_bodypix).
More reading:

* [Real-time Human Pose Estimation in the Browser with TensorFlow.js](https://medium.com/tensorflow/real-time-human-pose-estimation-in-the-browser-with-tensorflow-js-7dd0bc881cd5)
* [Integrating Ml5.js PoseNet model with Three.js](https://medium.com/@miss.akaplan/integrating-ml5-js-posenet-model-with-three-js-b19710e2862b) via Advait
* [Introducing BodyPix: Real-time Person Segmentation in the Browser with TensorFlow.js](https://medium.com/tensorflow/introducing-bodypix-real-time-person-segmentation-in-the-browser-with-tensorflow-js-f1948126c2a0)

## 3/11 - Class 3

Class notes:

Transfer learning is the improvement of learning in a new task through the transfer of knowledge from a related task that has already been learned. ([Source](https://machinelearningmastery.com/transfer-learning-for-deep-learning/))

What is feature extraction?
  * In a multi layer neural network, the final layer is known as the softmax
  * It takes a list of numbers from the network and "squashes" them into probabilities
  * The layer before this final layer is known as the logits, or feature vector
  * This is the "fingerprint" of the image, and can be used to compare images
  * [Good explanation here](https://observablehq.com/@nsthorat/how-to-build-a-teachable-machine-with-tensorflow-js)

Retraining a network
  * If we swap out the final layer, we can retrain it to classify what we want

Linear regression
  * The simplest forms of machine learning
  * Also known as "line fitting"
  * Can be linear regression or polynomial
  * Continuous output, as opposed to classification which is discrete

KNN

  * "Tell me who your neighbor is, and I'll tell you who you are"
  * "K-Nearest Neighbor" is a machine learning algorithm used for both classification and regression. It is a "lazy learning" algorithm due to the fact that there is really is no learning at all. New data points are classified / valued according to a distance comparison with every data point in a training set. (source)[https://github.com/nature-of-code/NOC-S17-2-Intelligence-Learning/blob/master/week3-classification-regression/README.md]
  * [Nice interactive demo here](https://observablehq.com/@nsthorat/how-to-build-a-teachable-machine-with-tensorflow-js) a bit further down the page

Examples using transfer learning:

* [Teachable Machine](https://teachablemachine.withgoogle.com/)
* [Pacman](https://storage.googleapis.com/tfjs-examples/webcam-transfer-learning/dist/index.html) [code here](https://github.com/tensorflow/tfjs-examples/tree/master/)
* [Objectifier](https://experiments.withgoogle.com/objectifier-spatial-programming)
* [Getting Alexa to Respond to Sign Language Using Your Webcam and Tensorflowjs](https://medium.com/tensorflow/getting-alexa-to-respond-to-sign-language-using-your-webcam-and-tensorflow-js-735ccc1e6d3f)

Additional material:

* [Nature of Code Part 2 "Intelligence and Learning" - week3-classification-regression ](https://github.com/nature-of-code/NOC-S17-2-Intelligence-Learning/tree/master/week3-classification-regression) - tons of good resources here
* [ml4a - Classification with KNN](https://github.com/ml4a/ml4a-guides/blob/master/notebooks/classification_kNN.ipynb)
* [ml4a - Linear Regression](https://github.com/ml4a/ml4a-guides/blob/master/notebooks/linear_regression.ipynb)
* [ml4a - Transfer Learning](https://github.com/ml4a/ml4a-guides/blob/master/notebooks/transfer-learning.ipynb)

## 2/25 - Class 2

Class notes:

* What is deep learning?
* What are neural networks?
* [A brief history of neural networks](http://www.andreykurenkov.com/writing/ai/a-brief-history-of-neural-nets-and-deep-learning/)
* Datasets
  * [Imagenet](http://www.image-net.org/)
  * [CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html)
* Pre-trained models
  * [Tensorflowjs models](https://github.com/tensorflow/tfjs-models)
  * [Mobilenets](https://ai.googleblog.com/2017/06/mobilenets-open-source-models-for.html)
* [Getting started with ml5](https://ml5js.org/docs/getting-started)
* For now we can use the [p5.js web editor](https://editor.p5js.org) - make an account to save your projects
* [Github](https://github.com/channelstudio/spring2019machinelearning-code/tree/master/wk02_image_classification) with code from the class

Additional material:

* [A Brief History of Neural Networks](http://www.andreykurenkov.com/writing/ai/a-brief-history-of-neural-nets-and-deep-learning/)
* [Nature of Code Chapter 10: Neural Networks](https://natureofcode.com/book/chapter-10-neural-networks/)
* [A Quick Introduction to Neural Networks](https://ujjwalkarn.me/2016/08/09/quick-intro-neural-networks/)
* [Let's Code a Neural Network from Scratch](https://medium.com/typeme/lets-code-a-neural-network-from-scratch-part-1-24f0a30d7d62)
* [Nature of Code Class Week 4](https://github.com/nature-of-code/NOC-S17-2-Intelligence-Learning/blob/master/week4-neural-networks/README.md) - tons of more resources here
* [ml5 image classifier using the p5js web editor](https://editor.p5js.org/ml5/sketches/rJ-C5AQ5X)
* [Setting up a local server with Python](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/set_up_a_local_testing_server)


## 2/18 - Class 1

Class notes: 

* What is machine learning?
* [Artificial intelligence vs machine learning vs deep learning](https://blogs.nvidia.com/blog/2016/07/29/whats-difference-artificial-intelligence-machine-learning-deep-learning-ai/)
* Community
  * [https://arxiv.org](https://arxiv.org)
* Tools
  * [Tensorflowjs](https://js.tensorflow.org/)
  * [p5.js](https://p5js.org/)
  * [ml5](https://ml5js.org)
* Types of learning
  * [Supervised vs Unsupervised learning](https://towardsdatascience.com/supervised-vs-unsupervised-learning-14f68e32ea8d)
  * Reinforcement learning (see [OpenAI gym](https://gym.openai.com/))
* Classification vs regression

### Use cases for Machine Learning
* Image classification
  * [cs231n.github.io/classification/](cs231n.github.io/classification/)
  * [Emoji Scavenger Hunt](https://experiments.withgoogle.com/emoji-scavenger)
  * [Giorgio Cam](https://experiments.withgoogle.com/giorgio-cam)
  * [Thing Translator](https://experiments.withgoogle.com/thing-translator)
  * [MoMA x Google](https://www.moma.org/calendar/exhibitions/history/identifying-art)
* Transfer learning
  * [Teachable Machine](https://experiments.withgoogle.com/teachable-machine)
* Image regression
* Localization and detection
  * [yolo](https://pjreddie.com/darknet/yolo/)
* Pose detection
  * [DensePose](http://densepose.org/)
  * [Posenet](https://github.com/tensorflow/tfjs-models/tree/master/posenet)
  * [Body Synth](https://experiments.withgoogle.com/body-synth)
  * [Move Mirror](https://experiments.withgoogle.com/move-mirror)
* Style transfer
  * [Gene Kogan](http://genekogan.com/works/style-transfer/)
* Image translation
  * [pix2pix](https://phillipi.github.io/pix2pix/)
* General adversarial networks (GAN)
  * [Big GAN](https://thegradient.pub/bigganex-a-dive-into-the-latent-space-of-biggan/)
  * [Original Big GAN paper](https://arxiv.org/abs/1809.11096)
  * [NVIDIA face GAN](https://research.nvidia.com/publication/2017-10_Progressive-Growing-of)
  * [https://thispersondoesnotexist.com/](https://thispersondoesnotexist.com/)
* Image to text
  * [Neural Storyteller](https://github.com/ryankiros/neural-storyteller)
  * [Word.camera](https://word.camera/)
* Text Generation
  * [GPT-2](https://blog.openai.com/better-language-models)
  * [Sunspring by Ross Goodwin](https://www.youtube.com/watch?v=LY7x2Ihqjmc)
* Dimensionality reduction
  * [Font-map](https://experiments.withgoogle.com/font-map)
  * [Infinite Drum Machine](https://experiments.withgoogle.com/drum-machine)
  * [Bird Sounds](https://experiments.withgoogle.com/bird-sounds)
  * [Curator Table](https://experiments.withgoogle.com/curator-table)
  * [X Degrees of Separation ](https://experiments.withgoogle.com/x-degrees-of-separation)
  * [Yale DHLab PixPlot](http://dhlab.yale.edu/projects/pixplot/)



Additional relevant resources:
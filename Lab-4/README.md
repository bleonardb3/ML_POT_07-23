
## Introduction:

ART is a library developed by "IBM Research" which is dedicated to adversarial machine learning. Its purpose is to allow rapid crafting and analysis of attacks and defense methods for machine learning models. ART provides an implementation for many state-of-the-art methods for attacking and defending classifiers.

    ART Demo: https://art-demo.mybluemix.net
    ART Blog: https://www.ibm.com/blogs/research/2018/04/ai-adversarial-robustness-toolbox/
    ART Github: https://github.com/IBM/adversarial-robustness-toolbox

In this notebook, you will work with Adversarial Robustness Toolbox (ART) and try to implement an adversarial attack and its defense on a trained model. You will work with a model trained on German Traffic Signs dataset and try to get the model to misclassify a stop sign.
## Dataset Citation

J. Stallkamp, M. Schlipsing, J. Salmen, and C. Igel. The German Traffic Sign Recognition Benchmark: A multi-class classification competition. In Proceedings of the IEEE International Joint Conference on Neural Networks, pages 1453–1460. 2011.

@inproceedings{Stallkamp-IJCNN-2011,
author = {Johannes Stallkamp and Marc Schlipsing and Jan Salmen and Christian Igel},
booktitle = {IEEE International Joint Conference on Neural Networks},
title = {The {G}erman {T}raffic {S}ign {R}ecognition {B}enchmark: A multi-class classification competition},
year = {2011},
pages = {1453--1460}
}
## Objectives:

Upon completing the lab, you will learn:

    How to load a Tensorflow trained model
    How to create an ART classifier object using the loaded model
    How to perfom an adversarial attack
    How to perfom a defense to make sure manipulated images can still be classified correctly


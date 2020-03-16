# Senior Project: Cluster Method to Strengthen Adversarial Defence on Deep Learning Models

Sirakorn Lamyai 2020: Cluster Method to Strengthen Adversarial Defence on Deep Learning Models,\
Bachelor of Engineering (Computer Engineering), Department of Computer Engineering, Faculty of Engineering, Kasetsart University\
Project advisor: Assoc. Prof. Dr. Jittat Fakcharoenphol, Assoc. Prof. Dr. Thanawin Rakthanmanon

## Abstract

A well-trained accurate machine learning model may suffer from adversarial attacks that can be easily carried out in the real world. Training robust models that withstand adversarial attacks thus becomes an important problem in machine learning. Adversarial training increases model robustness by including adversarial examples during the training. The quality of the model depends on the quality of the added examples.

This work considers two popular methods for adversarial example generation: the Fast Gradient Sign Method (FGSM) and the Projected Gradient Descent (PGD). While FSGM is very efficient, the generated examples are weak against stronger attacking methods, including the examples generated from the PGD. On the other hand, while PGD produces high quality examples, the procedure is time-consuming. In this work, we propose a simple method based on clustering to find a trade-off between the two methods for adversarial example generation. The experimental result in an equally tolerating model to PGD attacks despite the much faster runtime.

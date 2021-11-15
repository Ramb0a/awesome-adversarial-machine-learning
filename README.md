# Awesome Adversarial ML  [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

What is Adversarial Machine Learning? 

> An adversarial example is an input to a machine learning model that is intentionally designed by an attacker to fool the model into producing an incorrect output. [source](http://www.cleverhans.io/security/privacy/ml/2017/02/15/why-attacking-machine-learning-is-easier-than-defending-it.html)

For example start with an image - add a perterbed image and fool the model into a new and incorrect probability distribution at time of inference: 

![Adversary Image 1](adversary01.png)

![Adversary Image 2](adversary02.png)

> So far, it is much easier to design tricks like this that fool a model than it is to design models that can’t be fooled.  [source](http://www.cleverhans.io/security/privacy/ml/2017/02/15/why-attacking-machine-learning-is-easier-than-defending-it.html)

> Adversarial examples are hard to defend against because it is hard to construct a theoretical model of the adversarial example crafting process. Adversarial examples are solutions to an optimization problem that is non-linear and non-convex for many ML models, including neural networks. Because we don’t have good theoretical tools for describing the solutions to these complicated optimization problems, it is very hard to make any kind of theoretical argument that a defense will rule out a set of adversarial examples.  [source](http://www.cleverhans.io/security/privacy/ml/2017/02/15/why-attacking-machine-learning-is-easier-than-defending-it.html)

> From another point of view, adversarial examples are hard to defend against because they require machine learning models to produce good outputs for every possible input. Most of the time, machine learning models work very well but only work on a very small amount of all the many possible inputs they might encounter.  [source](http://www.cleverhans.io/security/privacy/ml/2017/02/15/why-attacking-machine-learning-is-easier-than-defending-it.html)

> Because of the massive amount of possible inputs, it is very hard to design a defense that is truly adaptive.  [source](http://www.cleverhans.io/security/privacy/ml/2017/02/15/why-attacking-machine-learning-is-easier-than-defending-it.html)

# Resources

[Volkwagen: The Scandal Explained](https://www.bbc.com/news/business-34324772) 

# References 

(2018) [Motivating the Rules of the Game for Adversarial Example Research](https://arxiv.org/abs/1807.06732)

(2018) [Audio Adversarial Examples: Targeted Attacks on Speech-to-Text](https://arxiv.org/abs/1801.01944)

(2018) [PixelDefend: Leveraging Generative Models to Understand and Defend against Adversarial Examples](https://arxiv.org/abs/1710.10766)

(2018) [Wild Patterns: Ten Years After the Rise of Adversarial Machine Learning](https://arxiv.org/abs/1712.03141)

(2017) [Adversarial Examples Are Not Easily Detected: Bypassing Ten Detection Methods](https://arxiv.org/abs/1705.07263)

(2017) [Delving into Transferable Adversarial Examples and Black-box Attacks](https://arxiv.org/abs/1611.02770)

(2017) [Adversarial Examples In The Physical World](https://arxiv.org/pdf/1607.02533v3.pdf)

(2017) [Towards Evaluating the Robustness of Neural Networks](https://arxiv.org/abs/1608.04644)

(2017) [Practical Black-Box Attacks against Deep Learning Systems using Adversarial Examples](https://arxiv.org/abs/1602.02697)

(2017) [Detecting Adversarial Attacks on Neural Network Policies with Visual Foresight](https://arxiv.org/abs/1710.00814)

(2017) [Adversarial attacks on neural network policies](https://arxiv.org/abs/1702.02284)

(2017) [Analysis of classifiers’ robustness to adversarial perturbations](https://link.springer.com/article/10.1007%2Fs10994-017-5663-3)

(2017) [Tactics of Adversarial Attacks on Deep Reinforcement Learning Agents](https://arxiv.org/abs/1703.06748)

(2017) [Delving into adversarial attacks on deep policies](https://arxiv.org/abs/1705.06452)

(2017)  [Adversarial Training Methods for Semi-Supervised Text Classification](https://arxiv.org/abs/1605.07725)

(2017) [Adversarial Examples for Semantic Segmentation and Object Detection](https://arxiv.org/pdf/1703.08603.pdf)

(2017) [Adversarial Examples for Evaluating Reading Comprehension Systems](https://arxiv.org/abs/1707.07328)

(2017) [Adversarial Machine Learning At Scale](https://arxiv.org/pdf/1611.01236.pdf)

(2017) [Ensemble Adversarial Training: Attacks and Defenses](https://arxiv.org/abs/1705.07204)

(2017) [Extending Defensive Distillation](https://arxiv.org/abs/1705.05264)

(2016) [DeepFool: a simple and accurate method to fool deep neural networks](https://arxiv.org/abs/1511.04599)

(2016) [The Limitations of Deep Learning in Adversarial Settings](https://arxiv.org/abs/1511.07528)

(2016) [Transferability in Machine Learning: from Phenomena to Black-Box Attacks using Adversarial Samples](https://arxiv.org/abs/1605.07277)

(2016) [Distillation as a Defense to Adversarial Perturbations against Deep Neural Networks](https://arxiv.org/pdf/1511.04508.pdf)

(2015) [Explaining and Harnessing Adversarial Examples](https://arxiv.org/abs/1412.6572)

(2015) [Deep Neural Networks are Easily Fooled: High Confidence Predictions for Unrecognizable Images](https://arxiv.org/abs/1412.1897)

(2014) [Intriguing properties of neural networks](https://arxiv.org/abs/1312.6199)

(2011) [Adversarial Machine Learning](https://people.eecs.berkeley.edu/~tygar/papers/SML2/Adversarial_AISEC.pdf)

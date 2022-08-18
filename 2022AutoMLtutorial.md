### Learning Curves for Decision Making in Supervised Machine Learning

Tutorial co-hosted at AutoML 2022. 

Date: July 25rd, 2022 (11:00-12:30)


### Slides

[<img src="GFX/pdffile.png" width="50" />](/metalearning/content/2022AutoML/tutorial_learning_curves.pdf){:target="_blank" rel="noopener"}
[<img src="GFX/youtube.png" width="50" />](https://www.youtube.com/watch?v=KPDZNNxrMqw){:target="_blank" rel="noopener"}

### Abstract

Learning curves have commonly been adopted in the context of machine learning to assess the performance of a learning algorithm with respect to a certain resource, e.g. the number of training examples or the number of training iterations. Learning curves have important applications in several contexts of machine learning, most importantly for the context of data acquisition, early stopping of model training and model selection. For example, by modeling the learning curves, one can assess at an early stage whether the algorithm and hyperparameter configuration have the potential to be a suitable choice, often speeding up the algorithm selection process. Some models answer the binary decision question of whether a certain algorithm at a certain budget will outperform a certain reference performance, whereas more complex models predict the entire learning curve of an algorithm. This tutorial presents a framework that categorizes learning curve approaches using three criteria: the decision situation that they address, the intrinsic learning curve question that they answer and the type of resources that they use. We present prominent methods from literature that facilitate learning curves for decision making and classify them into this framework. This tutorial follows an extensive survey paper that we recently published [(Mohr and van Rijn, 2022)](https://arxiv.org/abs/2201.12150){:target="_blank" rel="noopener"}.

Learning curves are extensively used in the AutoML literature, to speed up the combined hyperparameter and algorithm selection problem. When a candidate configuration seems to perform poorly at a low resource (e.g., after several epochs), it seems useful to spend computing budget at different configurations. Several techniques explicitly model and extrapolate learning curves (e.g., FABOLAS by Klein et al., 2017) whereas other methods implicitly use learning curves (e.g., Successive Halving by Jamieson et al., 2016). Unfortunately, there is no unambiguous nomenclature in the community to distinguish various types of learning curves and the behavior that these can exhibit. For example, learning curves of a neural network with as budget the increasing amount of epochs have different behavior than learning curves of a support vector machine with as budget the increasing amount of data. In this tutorial, we want to present the holistic view of the various types of learning curves that have been used in the literature, and the decision situation in which these learning curves can be used. Additionally, we aim to give an overview of the recent methods that have been developed using learning curves. We believe that any AutoML method should be aware of learning curve techniques, and by presenting this structured framework and the recent methods will help our community to better understand learning curves, thereby further improving the AutoML methods.

### Schedule:

* Introduction (10 mins, FM)
* Background on Learning Curves (20 mins, FM)
  * Definition
  * True and Empirical Learning Curves
  * Utility Curves
  * Shapes and Terminology of Learning Curves
  * Modeling a Learning Curve
* Types of Learning Curves (15 mins)
  * Learning Curves for Decision Making (20 mins, FM)
  * Use Cases
  * Technical Questions on Learning Curves
  * Resources for Inferences
* Literature Overview (40 mins, JvR)
  * Identification of Saturation Performance
  * Identification of Saturation Point
  * Finding the Utility-Based Stopping Point
  * Performance Bounding at Fixed Point(s)
  * Performance Prediction at Fixed Point
  * Performance Prediction at Any Point
  * Utility Prediction at Any Point
  * Performance at Any Point for Any Learner
* Outlook (5 mins, JvR)


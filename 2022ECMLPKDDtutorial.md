### Meta-Knowledge Transfer/Communication in Different Systems

Tutorial co-hosted at ECML/PKDD 2022. 

Date: September 23rd, 2022 (morning)

### Abstract

Machine Learning models exceed human performance in many benchmarks in areas such as image recognition and natural language processing. In order to achieve exceptional performance, several conditions need to be met. For example, a good model type needs to be chosen, the hyperparameters need to be set appropriately, and there needs to be sufficient data. As such, there is a dependence on a human expert controlling the learning process. Metalearning aims to support this human expert in these various learning tasks.

In recent years the meta-learning community has identified and addressed increasingly complex problems. Similar to our recently published book,“Metalearning: Applications to Automated Machine Learning and Data Mining”, we will address various problem settings that are of relevance to the ECML/PKDD community, such as Algorithm Selection, Hyperparameter optimization, Workflow (Pipeline) synthesis, architecture search and few-shot learning. Meta-learning aims to consolidate knowledge that has been acquired from earlier experience to better address these challenges.

Algorithm selection is concerned with the following question: when given a dataset and a set of algorithms, which of these algorithms would be most appropriate for this given dataset? Techniques mostly rely on so- called meta-features. Solutions for this problem have been proposed in a machine learning setting since the 1990s. Later, the problem definition has been extended to also optimise the various hyperparameters of an algorithm. Black-box optimization and various AutoML tools address these problems with the help of meta- learning. As such, having a good understanding of meta-learning is crucial in order to further improve AutoML systems.

More recently, a new problem type emerged from the field of meta-learning, focussing on problem settings where data on the (target) domain is scarce, but plenty of data from a related (source) domain is available (called few-shot learning). Solutions like fine-tuning, gradient-based meta-learning, and metric-based meta- learning attempt to transfer concepts from the source domain towards the target domain. Utilising these techniques, well-performing models can be trained on image-recognition benchmarks with as few as a single example per class.

In this tutorial, we take a problem-oriented approach, where for each problem setting we introduce the problem definition, the logical baselines, and what state-of-the-art methods are currently utilised. We will start with the earlier methods, and show how the more recent and complex methods logically build upon the simpler techniques. We will conclude with an overview of current challenges and state-of-the-art.

### Provisional Schedule:

* Welcome and Introduction (30m, JvR):
  * Illustrative example of a problem(Ch1)
  * Problem settings, explaining the relevance (Ch 1)
  * Structure of the Tutorial
* Meta-learning for Algorithm Selection (45m, PB):
  * Average ranking method(Ch2)
  * Algorithm Selection methods utilising meta-features (Ch 4)
  * Active Testing(Ch5)
  * Utilising Accuracy and Runtime (Ch 5)
  * Utilising Learning Curves (Ch5, Learning Curves Survey)
* Meta-learning for Pipeline Optimization (45m, FM)
  * Random Search and Grid Search (Ch 6)
  * Bayesian Optimization (Ch6)
  * Automating Workflow/Pipeline Design (Ch7)
  * AutoML Systems: Autosklearn and ML-Plan (Ch6)
* Coffee Break (30m)
* Meta-learning for Few-Shot learning (45m, HG)
  * Transfer Learning(Ch12)
  * Gradient-based meta-learning (MAML, Reptile, etc) (Ch 13)
  * Metric-based meta-learning (Prototypical networks) (Ch 13)
  * Bayesian Meta-Learning
* Other important considerations (40m) (PB+JvR)
  * Design of Configuration Spaces (Ch 8) 
  * Functional ANOVA (Ch 8)
  * Automating Data Science(Ch14)
  * Learning from Meta-data in Repositories (Ch 17)
  * Designing Complex applications (Ch 15)
* Outlook (5m, Ch 18)

### Meta-Knowledge Transfer/Communication in Different Systems

Tutorial co-hosted at [ECML/PKDD 2022](https://2022.ecmlpkdd.org/){:target="_blank" rel="noopener"}. 

Date: September 23rd, 2022 (10:30-13:30)

Location: ECML/PKDD Workshops and Tutorials, WTC & Minatec

This tutorial is given as combined tutorial/workshop. In the afternoon, the program will continue with [the workshop](/metalearning/2022ECMLPKDDworkshop). Beyond other sources, we will discuss the [book on metalearning](/metalearning/book). The tutorial will mostly be given live, in person (but it will be streamed for online participants). A very small part of the tutorial can be pre-recorded.

### Abstract

Machine Learning models exceed human performance in many benchmarks in areas such as image recognition and natural language processing. In order to achieve exceptional performance, several conditions need to be met. For example, a good model type needs to be chosen, the hyperparameters need to be set appropriately, and there needs to be sufficient data. As such, there is a dependence on a human expert controlling the learning process. Metalearning aims to support this human expert in these various learning tasks.

In recent years the meta-learning community has identified and addressed increasingly complex problems. Similar to our recently published book,“Metalearning: Applications to Automated Machine Learning and Data Mining”, we will address various problem settings that are of relevance to the ECML/PKDD community, such as Algorithm Selection, Hyperparameter optimization, Workflow (Pipeline) synthesis, architecture search and few-shot learning. Meta-learning aims to consolidate knowledge that has been acquired from earlier experience to better address these challenges.

Algorithm selection is concerned with the following question: when given a dataset and a set of algorithms, which of these algorithms would be most appropriate for this given dataset? Techniques mostly rely on so- called meta-features. Solutions for this problem have been proposed in a machine learning setting since the 1990s. Later, the problem definition has been extended to also optimise the various hyperparameters of an algorithm. Black-box optimization and various AutoML tools address these problems with the help of meta- learning. As such, having a good understanding of meta-learning is crucial in order to further improve AutoML systems.

More recently, a new problem type emerged from the field of meta-learning, focussing on problem settings where data on the (target) domain is scarce, but plenty of data from a related (source) domain is available (called few-shot learning). Solutions like fine-tuning, gradient-based meta-learning, and metric-based meta- learning attempt to transfer concepts from the source domain towards the target domain. Utilising these techniques, well-performing models can be trained on image-recognition benchmarks with as few as a single example per class.

In this tutorial, we take a problem-oriented approach, where for each problem setting we introduce the problem definition, the logical baselines, and what state-of-the-art methods are currently utilised. We will start with the earlier methods, and show how the more recent and complex methods logically build upon the simpler techniques. We will conclude with an overview of current challenges and state-of-the-art.


### Speakers
* [Pavel Brazdil](http://www.liaad.up.pt/area/pbrazdil/pavel-brazdil){:target="_blank" rel="noopener"}, University of Porto, Portugal
* [Jan N. van Rijn](https://www.universiteitleiden.nl/en/staffmembers/jan-van-rijn){:target="_blank" rel="noopener"}, Leiden University, The Netherlands
* [Henry Gouk](https://www.henrygouk.com/){:target="_blank" rel="noopener"}, University of Edinburgh, Scotland 
* [Felix Mohr](https://www.linkedin.com/in/felix-mohr-83464a220/){:target="_blank" rel="noopener"}, Universidad de La Sabana, Colombia

### Provisional Schedule:

* 10:30 - 10:45: Welcome and Introduction (15m, JvR):
  * Illustrative example of a problem ([Ch 1](https://link.springer.com/chapter/10.1007/978-3-030-67024-5_1){:target="_blank" rel="noopener"})
  * Problem settings, explaining the relevance ([Ch 1](https://link.springer.com/chapter/10.1007/978-3-030-67024-5_1){:target="_blank" rel="noopener"})
  * Structure of the Tutorial
* 10:45 - 11:25: Meta-learning for Algorithm Selection (40m, PB):
  * Average ranking method ([Ch 2](https://link.springer.com/chapter/10.1007/978-3-030-67024-5_2){:target="_blank" rel="noopener"})
  * Algorithm Selection methods utilising meta-features ([Ch 4](https://link.springer.com/chapter/10.1007/978-3-030-67024-5_4){:target="_blank" rel="noopener"})
  * Active Testing ([Ch 5](https://link.springer.com/chapter/10.1007/978-3-030-67024-5_5){:target="_blank" rel="noopener"})
  * Utilising Accuracy and Runtime ([Ch 5](https://link.springer.com/chapter/10.1007/978-3-030-67024-5_5){:target="_blank" rel="noopener"})
  * Utilising Learning Curves (FM, [Ch 5](https://link.springer.com/chapter/10.1007/978-3-030-67024-5_5){:target="_blank" rel="noopener"}, [Learning Curves Survey](https://arxiv.org/abs/2201.12150){:target="_blank" rel="noopener"})
* 11:25 - 12:00: Meta-learning for Pipeline Optimization (35m, FM)
  * Random Search and Grid Search ([Ch 6](https://link.springer.com/chapter/10.1007/978-3-030-67024-5_6){:target="_blank" rel="noopener"})
  * Bayesian Optimization ([Ch 6](https://link.springer.com/chapter/10.1007/978-3-030-67024-5_6){:target="_blank" rel="noopener"})
  * Automating Workflow/Pipeline Design ([Ch 7](https://link.springer.com/chapter/10.1007/978-3-030-67024-5_7){:target="_blank" rel="noopener"})
  * AutoML Systems: Autosklearn and ML-Plan ([Ch 6](https://link.springer.com/chapter/10.1007/978-3-030-67024-5_6){:target="_blank" rel="noopener"})
* 12:00 - 12:10: Q&A, Small break (10m)
* 12:10 - 12:50: Meta-learning for Few-Shot learning (40m, HG)
  * Transfer Learning ([Ch 12](https://link.springer.com/chapter/10.1007/978-3-030-67024-5_12){:target="_blank" rel="noopener"})
  * Gradient-based meta-learning (MAML, Reptile, etc) ([Ch 13](https://link.springer.com/chapter/10.1007/978-3-030-67024-5_13){:target="_blank" rel="noopener"})
  * Metric-based meta-learning (Prototypical networks) ([Ch 13](https://link.springer.com/chapter/10.1007/978-3-030-67024-5_13){:target="_blank" rel="noopener"})
  * Bayesian Meta-Learning
* 12:50 - 13:25: Advanced Topics (35m, PB+JvR)
  * Learning from Meta-data in Repositories (JvR, [Ch 17](https://link.springer.com/chapter/10.1007/978-3-030-67024-5_17){:target="_blank" rel="noopener"})
  * Functional ANOVA (JvR, [Ch 8](https://link.springer.com/chapter/10.1007/978-3-030-67024-5_8){:target="_blank" rel="noopener"})
  * Design of Configuration Spaces (PB, [Ch 8](https://link.springer.com/chapter/10.1007/978-3-030-67024-5_8){:target="_blank" rel="noopener"})
  * Automating Data Science (PB, [Ch 14](https://link.springer.com/chapter/10.1007/978-3-030-67024-5_14){:target="_blank" rel="noopener"})
  * Designing Complex applications (PB, [Ch 15](https://link.springer.com/chapter/10.1007/978-3-030-67024-5_15){:target="_blank" rel="noopener"})
* 13:25 - 13:30: Outlook, Q&A (5m, PB, [Ch 18](https://link.springer.com/chapter/10.1007/978-3-030-67024-5_18){:target="_blank" rel="noopener"})


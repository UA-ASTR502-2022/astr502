# ASTR 502 Data Mining and Machine Learning in Astronomy

## Location

Steward **R208** or Zoom : https://arizona.zoom.us/j/6849448207

## Textbook

Dive into Deep Learning (https://d2l.ai)

## Class Schedule

| ID |  Day |     Topic     |   Materials   | Presenters | Notes |
|----|------|---------------|---------------|------------|-------|
|  1 | 1/12 | Course Introduction          | | Tim | |
|  2 | 1/19 | Overview of Machine Learning | | Hung-Jin |[slides](./slides/ML_overview.pdf) |
|  3 | 1/24 | ML Applications in Astro | | Tim | 
|  4 | 1/26 | Gaussian Processes and NNs to sample parameter spaces quickly | | Supranta| 
|  5 | 1/31 | Linear Regression (theory & implementation) | d2l 3.1-3.3 | Wei Leong | [notebook](./notebooks/lec05_linear_regression_20220131/lec05_linear_regression_20220131.ipynb)|
|  6 | 2/2 | Logistic/Softmax Regression (theory & implementation) | d2l [§3.4](./d2l_briefs/3.4_softmax-regression.md), 3.5-3.7 | Chia-Lin | [slides](./slides/lec06_softmass_regression_20220202.pdf)|
|  7 | 2/7 | Multilayer Perceptrons | d2l [§4.1](./d2l_briefs/4.1_multilayer-perceptrons.md), 4.2, 4.3 <br> [notebook: MLP](./notebooks/[demo]%20pytorch%20softmax%20regression%20&%20MLP.ipynb)| Hina | [slides](https://docs.google.com/presentation/d/1zcgrALOXQZUYljuE4Y11QCcYA3UOW0iSjwpC_4bVtEQ/edit?usp=sharing) |
|  8 | 2/9 | Model Selection, Underfitting & Overfitting, Weight Decay, Dropout | d2l [§4.4](./d2l_briefs/4.4_model-selection.md), [§4.5](./d2l_briefs/4.5_weight-decay.md), [§4.6](./d2l_briefs/4.6_dropout.md) <br> [notebook: dropout](./notebooks/[demo]%20train%20MLP%20with%20dropout,%20L2%20Reg.ipynb)| Jeff | [slides](./slides/Sec4.4_4.6.pdf)
|  9 | 2/14 | Forward & Backward Prop, Vanishing gradient and parameter initialization | d2l [§4.7](./d2l_briefs/4.7_backprop.md), [§4.8](./d2l_briefs/4.8_numerical-stability-and-init.md) | Yang | [slides](./slides/Chapter4.7-4.8.pdf) |
| 10 | 2/16 | DL computation basics | d2l [§5.1](./d2l_briefs/5.1_model-construction.md), [§5.2](./notebooks/5.2_parameter-management.ipynb), [§5.4-5.6](./notebooks/5.4-5.6%20custom-layer,%20file%20IO,%20gpu.ipynb) | Joe | [slides](./slides/Chapter-5.pdf) <br> [notebook](./notebooks/Chapter-5-code-examples.ipynb)
| 11 | 2/21 | CNN basics 1 (Intro, Convolution, Padding & Stride) | d2l [§6.1](./d2l_briefs/6.1_why-cnn.md), [§6.2-§6.3](./notebooks/6.2-6.3%20CNN_1.ipynb) | Annie |[CNN 6.1-6.3.pdf](https://github.com/UA-ASTR502-2022/astr502/files/8130674/CNN.6.1-6.3.pdf) |
| 12 | 2/23 | CNN basics 2 (Channels, Pooling, LeNet) | d2l [§6.4-§6.6](./notebooks/6.4-6.6%20CNN_2.ipynb) | Patrick | [slides](./slides/CNN%20Lec%206.4-6.6.pdf) |
| 13 | 2/28 | Optimization Basics, Convexity | d2l [§11.1](./d2l_briefs/11.1_optimization-intro.md), [§11.2](./d2l_briefs/11.2_convexity.md) | Lily | [slides](./slides/Chapter11.1-11.2.pdf) |
| 14 | 3/2 | ------ Prelim, no lecture today ------ |  |  |
| 15 | 3/14 | Gradient Descent | d2l [§11.3](./d2l_briefs/11.3_gradient-descent.md), [§11.4-§11.5](./d2l_briefs/11.4-11.5_sgd-and-mgd.md) | Vivian | [slides](./slides/Gradient%20Descent.pptx) |
| 16 | 3/16 | Optimization algorithm 1 (momentum, adagrad) | d2l [§11.6](./d2l_briefs/11.6_momentum.md), [§11.7](./d2l_briefs/11.7_adagrad.md) | Hayden | [slides](./slides/Optimization1_11.6-11.7.pdf) |
| 17 | 3/21 | Optimization algorithm 2 (RMSProp, Adadelta, Adam) | d2l [§11.8](./d2l_briefs/11.8_rmsprop.md), [§11.9](./d2l_briefs/11.9_adadelta.md), [§11.10](./d2l_briefs/11.10_adam.md) | Gabriela | [slides](./slides/Optimization_RMSprop_Adadelta%26Adam.pdf) |
| 18 | 3/23 | Learning Rate decay, Batch Normalization | d2l [§11.11](./notebooks/11.11_lr-scheduler.ipynb), [§7.5](./d2l_briefs/7.5_batchnorm.md) | Haley | [slides](./slides/Optimization_7.5_11.11.pptx) |
| 19 | 3/28 | CNN architecture 1 (AlexNet, VGG) | d2l [§7.1](./notebooks/7.1_AlexNet.ipynb), [§7.2](./notebooks/7.2_VGG.ipynb) | Paul |
| 20 | 3/30 | CNN architecture 2 (NiN, GoogLeNet) | d2l [§7.3](./notebooks/7.3_NiN.ipynb), [§7.4](./notebooks/7.4_GoogLeNet.ipynb) | Jake | [slides](./slides/7.3-7.4_slides.pdf), [notes](./slides/7.3-7.4_discussion.pdf) |
| 21 | 4/4 | CNN architecture 3 (ResNet, DenseNet) | d2l [§7.6](./notebooks/7.6_ResNet.ipynb), [§7.7](./notebooks/7.7_DenseNet.ipynb) | Yu-Hsiu | [slides](https://slides.com/yvonnehuang-1/d)
| 22 | 4/6 | Features learned in ConvNet | [notebook1](./notebooks/%5Bdemo%5D%20ConvNet%20feature%20maps.ipynb), [notebook2](./notebooks/%5Bdemo%5D%20pretrained%20AlexNet%20feature%20maps.ipynb) | Hung-Jin | [slides](./slides/CNN_features.pdf)
| 23 | 4/11 | Term Project 1  | [paper1](https://arxiv.org/pdf/2103.01373.pdf), [paper2](https://arxiv.org/pdf/1704.02744.pdf) | Jeff, Patrick | |
| 24 | 4/13 | Term Project 2  | [paper](https://arxiv.org/pdf/2012.12392.pdf) | Chia-Lin | [slides](./slides/ML_final_ChiaLinKo.pdf)|
| 25 | 4/18 | Term Project 3  | [paper1](https://arxiv.org/abs/2106.13724), [paper2](https://arxiv.org/abs/2008.03833) | Joe, Jake | |
| 26 | 4/20 | Term Project 4  | [paper1](https://arxiv.org/abs/1702.00403), [paper2](https://arxiv.org/abs/1905.07424) | Hina, Colin | [slides2](./slides/Colin%20Leach%20project%20for%20ASTR%20502.pdf) |
| 27 | 4/25 | Term Project 5  | [paper1](https://arxiv.org/abs/2009.10673), [paper2](https://arxiv.org/abs/2005.12276) | Lily, Haley | |
| 28 | 4/27 | Term Project 6  | [paper1](https://arxiv.org/abs/2203.05583), TBD | Yu-Hsiu, Vivian | |
| 29 | 5/2  | Term Project 7  | TBD, [paper2](https://arxiv.org/abs/2011.10577) | Paul, Annie  | |
| 30 | 5/4  | Term Project 8  | [paper1](https://arxiv.org/abs/2011.12437), [paper2](https://arxiv.org/abs/1909.10963) | Hayden, Yang | |
| 31 | 5/9  | Term Project 9  | [paper1](https://arxiv.org/abs/1712.02777), [paper2](https://arxiv.org/abs/2011.12437) | Wei Leong, Maria Gabriela | |

## Links

- [Lecture Presentation sign up sheet](https://docs.google.com/spreadsheets/d/1fAXCX4KAjm6qUFpbhN5rk-7BbxeYci_f1RwhIoH6z3M/edit#gid=0)
  
- [Selected ML papers in Astronomy](./Term%20Projects/README.md)

- [ML papers in cosmology](https://github.com/georgestein/ml-in-cosmology/blob/master/README.md)

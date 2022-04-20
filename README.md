# STIMA Machine Learning Reading Group
The reading group is open to anyone who is interested in machine learning and who wants to meet up regularly to discuss ML research papers.

## Format
* One person is randomly designated the host for each session. They are responsible for choosing the paper to be discussed and for leading the discussion during the session. The host does not need to know the paper better than everyone else and does not need to prepare any presentation for the session.
* We meet Wednesdays 10:15-12:00 on odd weeks.
* We will meet in Thomas Bayes, B-building ([map](https://www.ida.liu.se/department/location/search.en.shtml?keyword=thomas+bayes)).

## Host intstructions
* Choose a paper that you think would be interesting to discuss in the reading group. In order to set a focus for the reading group we came up with the following short guidelines for how to choose papers:
  * The main topic of the paper should be core machine learning research. Try to avoid papers that just apply well known machine learning methods to specific application areas. 
  * Make sure the paper is of high quality. Read through it yourself and try to gauge its quality. As a guideline, think that it should be publishable at a top machine learning conference (i.e. the paper should be of such quality, it does not have to actually be a short conference paper).
  * If you want a second opinion on whether a paper is suitable feel free to ask me or anyone else who has been in the reading group previous years.
* Send out a link to the paper on the mailing list at least one week in advance.
* As the host it is also good to somewhat lead the discussion during the session. If you want you can give a short description of why you chose this paper, but there is no need for any proper presentation. It might be a good idea to come to the session prepared with a few discussion points, just to keep the conversation going.

## Schedule

__Week 7 (Feb 16)__
_- Host:_ Amanda

*This Looks Like That: Deep Learning for Interpretable Image Recognition*
<br>
Chaofan Chen, Oscar Li, Daniel Tao, Alina Barnett, Cynthia Rudin, Jonathan K. Su
<br>
https://papers.nips.cc/paper/2019/hash/adf7ee2dcf142b0e11888e72b43fcb75-Abstract.html

__Week 9 (Mar 2)__
_- Host:_ Filip

*Generative Modeling by Estimating Gradients of the Data Distribution*
<br>
Yang Song, Stefano Ermon
<br>
https://arxiv.org/abs/1907.05600

__Week 11 (Mar 16)__
_- Host:_ Fredrik

*Flow Network based Generative Models for Non-Iterative Diverse Candidate Generation*
<br>
Emmanuel Bengio, Moksh Jain, Maksym Korablyov, Doina Precup, Yoshua Bengio
<br>
https://papers.nips.cc/paper/2021/hash/e614f646836aaed9f89ce58e837e2310-Abstract.html

*Some related papers:*
<br>
* [GFlowNet Foundations paper](https://arxiv.org/abs/2111.09266) Yoshua Bengio, Tristan Deleu, Edward J. Hu, Salem Lahlou, Mo Tiwari, Emmanuel Bengio, "GFlowNet Foundations", arXiv:2111.09266, November 2021.
  * A longer paper introducing the model, underlying theory and various extensions

* [Trajectory Balance paper](https://arxiv.org/abs/2201.13259) Nikolay Malkin, Moksh Jain, Emmanuel Bengio, Chen Sun, Yoshua Bengio, “Trajectory Balance: Improved Credit Assignment in GFlowNets", arXiv:2201.13259, January 2022.
  * Here they introduce a more efficient training objective for the model.

* [Energy-Based GFlowNet paper](https://arxiv.org/abs/2202.01361) Dinghuai Zhang, Nikolay Malkin, Zhen Liu, Alexandra Volokhova, Aaron Courville, Yoshua Bengio, “Generative Flow Networks for Discrete Probabilistic Modeling", arXiv:2202.01361, February 2022.
  * Here they show how the GFlowNet model can be combined with an EBM to learn the energy function/target distribution from data. They also discuss how to build an efficient MCMC proposal for discrete spaces using the learnt GFlowNet.

* [Causal Graph Bayesian Posterior paper](https://arxiv.org/abs/2202.13903) Tristan Deleu, António Góis, Chris Emezue, Mansi Rankawat, Simon Lacoste-Julien, Stefan Bauer, Yoshua Bengio, “Bayesian Structure Learning with Generative Flow Networks", arXiv:2202.13903, February 2022.
  * Here they use the method for learning a Bayesian network

__Week 13 (Mar 30)__
_- Host:_ Josef

*Dangers of Bayesian Model Averaging under Covariate Shift*
<br>
Pavel Izmailov, Patrick Nicholson, Sanae Lotfi, Andrew G. Wilson
<br>
https://proceedings.neurips.cc/paper/2021/hash/1ab60b5e8bd4eac8a7537abb5936aadc-Abstract.html \+ Supplemental

Our rating : 3.17 ± 0.37

*Some related papers:*

* [What are bayesian neural network posteriors really like?](https://proceedings.mlr.press/v139/izmailov21a.html) Details on HMC sampling of the posterior in the main paper can be found here.
* Priors for Bayesian neural networks:
  * [Bayesian Neural Network Priors Revisited](https://arxiv.org/abs/2102.06571)
  * [Priors in Bayesian Deep Learning: A Review](https://arxiv.org/abs/2105.06868)
* Some background on covariate shift/domain shift:
  * [Domain Adaptation for Statistical Classifiers](https://www.jair.org/index.php/jair/article/view/10454)
  * [Out of Distribution Generalization in Machine Learning](https://arxiv.org/abs/2103.02667)
  * [Benchmarking Neural Network Robustness to Common Corruptions and Perturbations](https://arxiv.org/abs/1903.12261)


__Week 15 (Apr 13)__
_- Host:_ Joel

*The Neural Hawkes Process: A Neurally Self-Modulating Multivariate Point Process*
<br>
Hongyuan Mei, Jason Eisner
<br>
https://arxiv.org/abs/1612.09328

Our rating : 3.00 ± 0.53

*Some related papers:*
  * [Neural Jump Stochastic Differential Equations](https://arxiv.org/abs/1905.10403)
  * [Neural Spatio-Temporal Point Processes](https://arxiv.org/abs/2011.04583)

__Week 17 (Apr 27)__
_- Host:_ Per

*Posterior Network: Uncertainty Estimation without OOD Samples via Density-Based Pseudo-Counts*
<br>
Bertrand Charpentier, Daniel Zügner, Stephan Günnemann
<br>
https://proceedings.neurips.cc/paper/2020/hash/0eac690d7059a8de4b48e90f14510391-Abstract.html

*Some related papers:*
  * [Predictive Uncertainty Estimation via Prior Networks](https://proceedings.neurips.cc/paper/2018/hash/3ea2db50e62ceefceaf70a9d9a56a6f4-Abstract.html)
  * [Natural Posterior Network: Deep Bayesian Uncertainty for Exponential Family Distributions](https://arxiv.org/abs/2105.04471) 

__Week 19 (May 11)__
_- Host:_ Anton

__Week 21 (May 25)__
_- Host:_ Magnus

__Week 23 (Jun 8)__
_- Host:_ Hariprasath

__Week 25 (Jun 22)__
_- Host:_ TBA

## Topics Discussed VT 2021

__Week 5 (Feb 2): Meta-learning / few-shot learning__
_- Responsible:_ FE, AmA

Model-Agnostic Meta-Learning for Fast Adaptation of Deep Networks
<br>
Chelsea Finn, Pieter Abbeel, Sergey Levine
<br>
Proceedings of the 34th International Conference on Machine Learning, PMLR 70:1126-1135, 2017.
<br>
http://proceedings.mlr.press/v70/finn17a.html

__Week 7 (Feb 16): Meta-learning / few-shot learning__
_- Responsible:_ FE, AmA

Infinite Mixture Prototypes for Few-Shot Learning
<br>
Kelsey R. Allen, Evan Shelhamer, Hanul Shin, Joshua B. Tenenbaum
<br>
International Conference on Machine Learning (ICML), 2019
<br>
http://proceedings.mlr.press/v97/allen19b/allen19b.pdf



__Week 9 (Mar 2): Explainability/interpretability__
_- Responsible:_ JF, HM

Neural Additive Models: Interpretable Machine Learning with Neural Nets
<br>
https://arxiv.org/abs/2004.13912


__Week 12 (Mar 23): Explainability/interpretability__
_- Responsible:_ JF, HM
Understanding Black-box Predictions via Influence Functions
<br>
Pang Wei Koh, Percy Liang
<br>
Proceedings of the 34th International Conference on Machine Learning, PMLR 70:1885-1894, 2017.
<br>
http://proceedings.mlr.press/v70/koh17a.html


__Week 14 (Apr 6): Self-supervised learning / contrastive learning__
_- Responsible:_ AzA, JO

_Main paper:_ <br>
Representation Learning with Contrastive Predictive Coding<br>
Aaron van den Oord, Yazhe Li, Oriol Vinyals<br>
https://arxiv.org/abs/1807.03748

_Additional paper:_<br>
On Mutual Information Maximization for Representation Learning <br>
Michael Tschannen, Josip Djolonga, Paul K. Rubenstein, Sylvain Gelly, Mario Lucic<br>
https://arxiv.org/abs/1907.13625<br>


__Week 16 (Apr 20): Self-supervised learning / contrastive learning__
_- Responsible:_ AzA, JO

A Simple Framework for Contrastive Learning of Visual Representations
<br>
https://arxiv.org/pdf/2002.05709.pdf


__Week 18 (May 4): Normalizing flows (for variational inference)__
_- Responsible:_ SB, HG

SurVAE Flows: Surjections to Bridge the Gap between VAEs and Flows (https://arxiv.org/pdf/2007.02731.pdf)
<br>
Didrik Nielsen, Priyank Jaini, Emiel Hoogeboom, Ole Winther, Max Welling


__Week 21 (May 25): Normalizing flows (for variational inference)__
_- Responsible:_ SB, HG

Wehenkel, Antoine, and Gilles Louppe. "Graphical normalizing flows."
<br>
In International Conference on Artificial Intelligence and Statistics, pp. 37-45. PMLR, 2021.
<br>
Link : http://proceedings.mlr.press/v130/wehenkel21a/wehenkel21a.pdf




__Week 25 (Jun 22): Time series forecasting with ML__
_- Responsible:_ JW, MFS

Title: "A Hybrid Method for Exponential Smoothing and Recurrent Neural Networks for the Time Series Forecasting."
<br>
Link: https://www.sciencedirect.com/science/article/pii/S0169207019301153
<br><br>
This paper is a part of a contest (https://en.wikipedia.org/wiki/Makridakis_Competitions); it does not contain a comparison with other models or result sections! For the comparison and result sections, please see Table -1 & 2 from the following paper.
<br><br>
Title: "The M4 Competition: Results, Findings, Conclusion and Way Forward."
<br>
Link: https://www.sciencedirect.com/science/article/pii/S0169207018300785



__Week ?? (Jun ??): Time series forecasting with ML__
_- Responsible:_ JW, MFS


Probabilistic forecasting with temporal convolutional neural network<br>
Yitian Chen, Yanfei Kang, Yixiong Chen, Zizhuo Wang
<br>
Link: https://www.sciencedirect.com/science/article/abs/pii/S0925231220303441

## Topics discussed VT 2020

__Feb 4: Attention 1 (FL)__ 

_Main discussion paper:_ Xu et al. (2015) Show, Attend and Tell: Neural Image Caption Generation with Visual Attention, https://arxiv.org/abs/1502.03044

_Additional papers:_
* Bahdanau et al. (2014), Neural Machine Translation by Jointly Learning to Align and Translate, https://arxiv.org/abs/1409.0473
* Vaswani et al. (2017) Attention Is All You Need, https://arxiv.org/abs/1706.03762
* Chaudhari et al. (2019) An Attentive Survey of Attention Models, https://arxiv.org/abs/1904.02874

__Feb 18: Attention 2 (HG)__

_Main discussion paper:_ Vaswani et al. (2017) Attention is All You Need, https://arxiv.org/abs/1706.03762

_Follow-up paper:_ Devlin et al. (2018) BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding, https://arxiv.org/abs/1810.04805

__Mar 3: Out-of-distribution 1 (AA,JO)__

_Main discussion paper:_ https://arxiv.org/abs/1807.02588

_Additional papers:_ 
* https://arxiv.org/abs/1910.04241
* https://arxiv.org/abs/1511.05644

__Mar 17:__  _Canceled_

__Mar 31: Out-of-distribution 2 (AE)__

_Main discussion paper:_
* What Uncertainties Do We Need in Bayesian Deep Learning for Computer Vision?
https://arxiv.org/abs/1703.04977

_Related papers:_
* Sampling-free Epistemic Uncertainty Estimation Using Approximated Variance Propagation
https://arxiv.org/abs/1908.00598
* Uncertainty Estimates and Multi-Hypotheses Networks for Optical Flow
https://arxiv.org/abs/1802.07095

__Apr 14: Gaussian processes + deep learning 1 (AO,AK,JW)__
_E.g. Deep GP, Deep Kernel Learning_

_Main discussion paper:_
* Deep Kernel Learning http://proceedings.mlr.press/v51/wilson16.pdf.

_Related papers:_
* Gaussian Process Kernels for Pattern Discovery and Extrapolation http://proceedings.mlr.press/v28/wilson13.pdf (explaining the spectral mixture base kernel)
* Kernel Interpolation for Scalable Structured Gaussian Processes (KISS-GP)  http://proceedings.mlr.press/v37/wilson15.pdf (explaining the KISS-GP approach used for covariance approximation)

__Apr 28: Gaussian processes + deep learning 2 (AO,AK,JW)__
_E.g. Deep GP, Deep Kernel Learning_

* Stochastic Variational Deep Kernel Learning https://papers.nips.cc/paper/6426-stochastic-variational-deep-kernel-learning.pdf
* Learning Scalable Deep Kernels with Recurrent Structure http://jmlr.org/papers/volume18/16-498/16-498.pdf

If you are interested in learning more about LSTMs (for the second paper), you could also have a look at:
https://www.researchgate.net/publication/13853244_Long_Short-term_Memory


__May 12: Graph Neural Networks 1 (MM, FE, JK)__

* Main paper: Semi-Supervised Classification with Graph Convolutional Networks https://arxiv.org/abs/1609.02907

* Additional reading/background paper: Convolutional Neural Networks on Graphs with Fast Localized Spectral Filtering https://papers.nips.cc/paper/6081-convolutional-neural-networks-on-graphs-with-fast-localized-spectral-filtering.pdf

 
__May 26: Graph Neural Networks 2 (MM, FE, JK)__


* Main paper: How Powerful are Graph Neural Networks? https://cs.stanford.edu/people/jure/pubs/gin-iclr19.pdf

* Additional reading/background paper: Inductive Representation Learning on Large Graphs https://cs.stanford.edu/people/jure/pubs/graphsage-nips17.pdf



__Jun 9: Normalizing flows and GANs 1 (FJL, AR, GH)__

* Normalizing Flows: An Introduction and Review of Current Methods
https://arxiv.org/abs/1908.09257

* Glow: Generative Flow with Invertible 1x1 Convolutions
http://papers.nips.cc/paper/8224-glow-generative-flow-with-invertible-1x1-con


__Jun 23: Normalizing flows and GANs 2 (FJL, AR, GH)__

* Improved Training of Wasserstein GANs
https://papers.nips.cc/paper/7159-improved-training-of-wasserstein-gans

GAN background papers:

* Generative adversarial nets
http://papers.nips.cc/paper/5423-generative-adversarial-nets

* Wasserstein Generative Adversarial Networks
http://proceedings.mlr.press/v70/arjovsky17a.html


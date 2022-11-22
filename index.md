---
layout: default
title: Homepage
nav_order: 1
permalink: /
---

<img style="width:200px;float:right;margin:0 0px 12px 12px" src="{{site.url}}/assets/images/jiaxin.jpg">

I am a postdoctoral researcher working with [Emily B. Fox](https://statistics.stanford.edu/people/emily-b-fox) at Stanford University. 
I work on probabilistic modeling and inference for machine learning. 
My research aims at bridging the gap between data modeling (e.g., generative models and Bayesian methods) and algorithmic modeling (e.g., neural networks and spectral methods) by addressing challenging inferential questions at the interface of them, such as variational inference and gradient estimation, sampling and optimization, score-based learning, and predictive uncertainty estimation. 
<!-- I have worked on topics including approximate inference, Gaussian processes, kernel/spectral methods, generative models, and Bayesian neural networks.  -->

Before moving to Stanford I spent two wonderful years (1 year remotely) with the [Machine Learning and Statistics group](https://www.microsoft.com/en-us/research/theme/machine-learning-statistics/) at [Microsoft Research New England](https://www.microsoft.com/en-us/research/lab/microsoft-research-new-england/).
I obtained my PhD in Computer Science (2015-2020) from Tsinghua University, advised by [Jun Zhu](http://ml.cs.tsinghua.edu.cn/~jun).
During my graduate years I have spent a summer at [DeepMind](https://deepmind.com/) as a research scientist intern and visited [Vector Institute](https://vectorinstitute.ai/).
I have also spent a summer interning at [RIKEN-AIP](https://aip.riken.jp/), Tokyo. 
I received my B.E. in Computer Science at Tsinghua University. 
<!-- My CV can be downloaded from this link: [[pdf]](https://thjashin.github.io/docs/Curriculum_Vitae.pdf). -->

<a href="https://github.com/thjashin"><img style="vertical-align: middle; margin: 0 16px 0 12px" src="{{site.url}}/assets/images/github/GitHub-Mark-32px.png" >Github</a>
<a href="https://twitter.com/thjashin"><img style="width:32px; vertical-align: middle; margin: 0 12px 0 16px" src="{{site.url}}/assets/images/twitter/Twitter_Logo_Blue.png" >Twitter</a>


## News
{: .d-inline-block :}

* Our work on gradient estimation for discrete distributions won the [NeurIPS 2022 Outstanding Paper Award](https://blog.neurips.cc/2022/11/21/announcing-the-neurips-2022-awards/)!
* I am an area chair for [AISTATS 2023](http://aistats.org/aistats2023/).
* I am a [top reviewer](https://neurips.cc/Conferences/2022/ProgramCommittee) for [NeurIPS 2022](https://neurips.cc/).

## Selected Publications
{: .d-inline-block :}

<a href="/publications.html" style="color:inherit;">MORE</a> 
{: .label .label-red :}
<!-- {: .fs-9 } -->


### Probabilistic Inference and Gradient Estimation

A Finite-Particle Convergence Rate for Stein Variational Gradient Descent
{: .fs-5 .mb-1 .text-grey-dk-200}
**Jiaxin Shi**, Lester Mackey. 
{: .mb-1}
Preprint, 2022.
[[pdf]](https://arxiv.org/pdf/2211.09721.pdf)
[[abs]](https://arxiv.org/abs/2211.09721)

Gradient Estimation with Discrete Stein Operators
{: .fs-5 .mb-1 .text-grey-dk-200}
**Jiaxin Shi**, Yuhao Zhou, Jessica Hwang, Michalis K. Titsias, Lester Mackey.
{: .mb-1}
NeurIPS, 2022.
[[pdf]](https://arxiv.org/pdf/2202.09497.pdf)
[[abs]](https://arxiv.org/abs/2202.09497)
[[code]](https://github.com/thjashin/rodeo)
{: .mb-1}
<span style="color:black"><b>NeurIPS 2022 Outstanding Paper Award</b></span>.

Double Control Variates for Gradient Estimation in Discrete Latent Variable Models
{: .fs-5 .mb-1 .text-grey-dk-200}
Michalis K. Titsias, **Jiaxin Shi**.
{: .mb-1}
AISTATS, 2022.
[[pdf]](https://arxiv.org/pdf/2111.05300.pdf)
[[abs]](https://arxiv.org/abs/2111.05300)
[[code]](https://github.com/thjashin/double-cv)

Sampling with Mirrored Stein Operators
{: .fs-5 .mb-1 .text-grey-dk-200}
**Jiaxin Shi**, Chang Liu, Lester Mackey.
{: .mb-1}
ICLR, 2022.
[[pdf]](https://arxiv.org/pdf/2106.12506.pdf)
[[abs]](https://arxiv.org/abs/2106.12506)
[[code]](https://github.com/thjashin/mirror-stein-samplers)
[[slides]](https://thjashin.github.io/talks/mirror-stein-samplers.pdf)
{: .mb-1 .text-grey-dk-300}
Spotlight Presentation (top 5.1%). 

### Understanding Deep Learning, Representation Learning

Neural Eigenfunctions Are Structured Representation Learners
{: .fs-5 .mb-1 .text-grey-dk-200}
Zhijie Deng\*, **Jiaxin Shi**\*, Hao Zhang, Peng Cui, Cewu Lu, Jun Zhu. 
{: .mb-1}
Preprint, 2022.
[[pdf]](https://arxiv.org/pdf/2210.12637.pdf)
[[abs]](https://arxiv.org/abs/2210.12637)
<!-- [[code]](https://github.com/thudzj/NeuralEigenFunction) -->

NeuralEF: Deconstructing Kernels by Deep Neural Networks
{: .fs-5 .mb-1 .text-grey-dk-200}
Zhijie Deng, **Jiaxin Shi**, Jun Zhu. 
{: .mb-1}
ICML, 2022.
[[pdf]](https://arxiv.org/pdf/2205.00165.pdf)
[[abs]](https://arxiv.org/abs/2205.00165)
[[code]](https://github.com/thudzj/NeuralEigenFunction)

Neural Networks as Inter-domain Inducing Points
{: .fs-5 .mb-1 .text-grey-dk-200}
Shengyang Sun\*, **Jiaxin Shi**\*, Roger Grosse. 
{: .mb-1}
AABI Symposium, 2020.
[[pdf]](https://openreview.net/pdf?id=NgqYp7sAW6t)
[[slides]](http://thjashin.github.io/talks/nn-as-sparse-gp.pdf)
[[video]](https://www.youtube.com/watch?v=y29G0aRshy0&t=2s)

### Score-based Learning

Nonparametric Score Estimators
{: .fs-5 .mb-1 .text-grey-dk-200}
Yuhao Zhou, **Jiaxin Shi**, Jun Zhu.
{: .mb-1}
ICML, 2020.
[[pdf]](https://arxiv.org/pdf/2005.10099)
[[abs]](https://arxiv.org/abs/2005.10099)
[[code]](https://github.com/miskcoo/kscore)
[[slides]](http://ml.cs.tsinghua.edu.cn/~yuhao/slides/nonparametric%20score%20estimators,%20icml2020.pdf)

Sliced Score Matching: A Scalable Approach to Density and Score Estimation
{: .fs-5 .mb-1 .text-grey-dk-200}
Yang Song\*, Sahaj Garg\*, **Jiaxin Shi**, Stefano Ermon.
{: .mb-1}
UAI, 2019.
[[pdf]](https://arxiv.org/pdf/1905.07088)
[[abs]](https://arxiv.org/abs/1905.07088)
[[code]](https://github.com/ermongroup/sliced_score_matching)
[[video]](https://www.youtube.com/watch?v=lapaQrdYIWg)
[[blog]](https://ermongroup.github.io/blog/ssm/)
{: .mb-1}
Oral Presentation (top 8.7%). 

A Spectral Approach to Gradient Estimation for Implicit Distributions
{: .fs-5 .mb-1 .text-grey-dk-200}
**Jiaxin Shi**, Shengyang Sun, Jun Zhu.
{: .mb-1}
ICML, 2018. 
[[pdf]](https://arxiv.org/pdf/1806.02925.pdf)
[[abs]](https://arxiv.org/abs/1806.02925)
[[code]](https://github.com/thjashin/spectral-stein-grad)
[[slides]](http://ml.cs.tsinghua.edu.cn/~jiaxin/talks/ssge-icml-18.pdf)

### Predictive Uncertainty Estimation

Scalable Variational Gaussian Processes via Harmonic Kernel Decomposition
{: .fs-5 .mb-1 .text-grey-dk-200}
Shengyang Sun, **Jiaxin Shi**, Andrew Gordon Wilson, Roger Grosse.
{: .mb-1}
ICML, 2021.
[[pdf]](https://arxiv.org/pdf/2106.05992)
[[abs]](https://arxiv.org/abs/2106.05992)
[[code]](https://github.com/ssydasheng/Harmonic-Kernel-Decomposition)

Sparse Orthogonal Variational Inference for Gaussian Processes
{: .fs-5 .mb-1 .text-grey-dk-200}
**Jiaxin Shi**, Michalis K. Titsias, Andriy Mnih.
{: .mb-1}
AISTATS, 2020.
[[pdf]](https://arxiv.org/pdf/1910.10596)
[[abs]](https://arxiv.org/abs/1910.10596)
[[code]](https://github.com/thjashin/solvegp)
[[slides]](http://ml.cs.tsinghua.edu.cn/~jiaxin/talks/solvegp-aistats.pdf)
{: .mb-1}
Best Student Paper Runner-Up at [AABI](http://approximateinference.org/), 2019.

Functional Variational Bayesian Neural Networks
{: .fs-5 .mb-1 .text-grey-dk-200}
Shengyang Sun\*, Guodong Zhang\*, **Jiaxin Shi**\*, Roger Grosse.
{: .mb-1}
ICLR, 2019.
[[pdf]](https://arxiv.org/pdf/1903.05779.pdf)
[[abs]](https://arxiv.org/abs/1903.05779)
[[code]](https://github.com/ssydasheng/FBNN)
[[video]](https://slideslive.com/38922672/invited-talk-functional-variational-bayesian-neural-networks)

## Software
{: .d-inline-block :}

During my PhD studies I led the development of ZhuSuan [[github]](https://github.com/thu-ml/zhusuan) [[doc]](https://zhusuan.readthedocs.io) [[arxiv]](https://arxiv.org/abs/1709.05870), 
an open-source differentiable probabilistic programming project based on Tensorflow. 

<!--
ZhuSuan: A Library for Bayesian Deep Learning
{: .fs-5 .mb-1 .text-grey-dk-300}
**Jiaxin Shi**, Jianfei Chen, Jun Zhu, Shengyang Sun, Yucen Luo, Yihong Gu, and Yuhao Zhou, 2017
{: .mb-1}

<img style=" width: 400px;margin: 0 0 0 0" src="{{site.url}}/assets/images/zhusuan.png">
ZhuSuan: A Library for Bayesian Deep Learning
{: .fs-6 .fw-300 }

[GitHub](https://github.com/thu-ml/zhusuan){: .btn .btn-primary .fs-5 .mb-4 .mb-md-0 .mr-2 } [Documentation](https://zhusuan.readthedocs.io){: .btn .fs-5 }
-->



<!-- ## Curriculum Vitae
{: .d-inline-block :} -->



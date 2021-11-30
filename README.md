# Fourier Features Let Networks Learn  High Frequency Functions in Low Dimensional Domains
### [Project Page](https://bmild.github.io/fourfeat/) | [Paper](https://arxiv.org/abs/2006.10739)
[![Open Demo in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tancik/fourier-feature-networks/blob/master/Demo.ipynb)<br>

[Matthew Tancik](http://tancik.com/)\*<sup>1</sup>,
[Pratul P. Srinivasan](https://people.eecs.berkeley.edu/~pratul/)\*<sup>1,2</sup>,
[Ben Mildenhall](https://people.eecs.berkeley.edu/~bmild/)\*<sup>1</sup>,
[Sara Fridovich-Keil](https://people.eecs.berkeley.edu/~sfk/)<sup>1</sup>,
[Nithin Raghavan](https://www.linkedin.com/in/nithinraghavan//)<sup>1</sup>,
[Utkarsh Singhal](https://scholar.google.com/citations?user=lvA86MYAAAAJ&hl=en)<sup>1</sup>,
[Ravi Ramamoorthi](http://cseweb.ucsd.edu/~ravir/)<sup>3</sup>,
[Jonathan T. Barron](http://jonbarron.info/)<sup>2</sup>,
[Ren Ng](https://www2.eecs.berkeley.edu/Faculty/Homepages/yirenng.html)<sup>1</sup><br>

<sup>1</sup>UC Berkeley, <sup>2</sup>Google Research, <sup>3</sup>UC San Diego <br>
<sup>*</sup>denotes equal contribution


## Abstract
![Teaser Image](https://user-images.githubusercontent.com/3310961/84946597-cdf59800-b09d-11ea-8f0a-e8aaeee77829.png)

We show that passing input points through a simple Fourier feature mapping enables a multilayer perceptron (MLP) to learn high-frequency functions in low-dimensional problem domains. These results shed light on recent advances in computer vision and graphics that achieve state-of-the-art results by using MLPs to represent complex 3D objects and scenes. Using tools from the neural tangent kernel (NTK) literature, we show that a standard MLP fails to learn high frequencies both in theory and in practice. To overcome this spectral bias, we use a Fourier feature mapping to transform the effective NTK into a stationary kernel with a tunable bandwidth. We suggest an approach for selecting problem-specific Fourier features that greatly improves the performance of MLPs for low-dimensional regression tasks relevant to the computer vision and graphics communities.

## Code
We provide a [demo IPython notebook](https://colab.research.google.com/github/tancik/fourier-feature-networks/blob/master/Demo.ipynb) as a simple reference for the core idea. The scripts used to generate the paper plots and tables are located in the [Experiments](https://github.com/tancik/fourier-feature-networks/tree/master/Experiments) directory.

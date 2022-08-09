# Realistic Gramophone Noise Synthesis using a diffusion model

Official repository of the paper:

> E. Moliner and V. Välimäki,, "Realistic Gramophone Noise Synthesis using a diffusion model", in Proceedings of the 25th International Conference on Digital Audio Effects (DAFx20in22), Vienna, Austria, September 2022


## Abstract
This paper introduces a novel data-driven strategy for synthesizing gramophone noise audio textures. A diffusion probabilistic model is applied to generate highly realistic quasiperiodic noises. The proposed model is designed to generate samples of length equal to one disk revolution, but a method to generate plausible periodic variations between revolutions is also proposed. A guided approach is also applied as a conditioning method, where an audio signal generated with manually-tuned signal processing is refined via reverse diffusion to improve realism. The method has been evaluated in a subjective listening test, in which the participants were often unable to recognize the synthesized signals from the real ones. The synthetic noises produced with the best proposed unconditional method are statistically indistinguishable from real noise recordings. This work shows the potential of diffusion models for highly realistic audio synthesis tasks.

<p align="center">
<img src="https://raw.githubusercontent.com/eloimoliner/gramophone_noise_synth/main/colab/guided_dffusion.png" alt="Sampling scheme"
width="700px"></p>

Listen to our [audio samples](http://research.spa.aalto.fi/publications/papers/dafx22-gramophone-synth/)

## Usage
To easily test our pretrained model, we recommend using the colab notebook. 
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/eloimoliner/gramophone_noise_synth/blob/main/colab/demo.ipynb)

---
title: "Synthesizing human-like sketches from natural images using a conditional convolutional decoder"
authors: '<b>Moritz Kampelmühler</b>, Axel Pinz'
collection: publications
permalink: /publications/synthesizing_human_like_sketches
excerpt: 'This paper presents a fully convolutional end-to-end architecture that is able to synthesize human-like sketches of objects in natural images with potentially cluttered background.'
date: 2020-03-02
venue: '2020 IEEE Winter Conference on Applications of Computer Vision (WACV)'
paperurl: '/files/synthesizing_human_like_sketches.pdf'
citation: 
---
[[pdf]]({{ site.baseurl }}/files/synthesizing_human_like_sketches.pdf)
[[poster]]({{ site.baseurl }}/files/synthesizing_human_like_sketches_poster.pdf)

![sample image]({{ site.baseurl }}/images/synthesizing_human_like_sketches_sample.png)
<br/><br/>
Humans are able to precisely communicate diverse concepts by employing sketches, a highly reduced and abstract shape based representation of visual content. We propose, for the first time, a fully convolutional end-to-end architecture that is able to synthesize human-like sketches of objects in natural images with potentially cluttered background. To enable an architecture to learn this highly abstract mapping, we employ the following key components: (1) a fully convolutional encoder-decoder structure, (2) a perceptual similarity loss function operating in an abstract feature space and (3) conditioning of the decoder on the label of the object that shall be sketched. Given the combination of these architectural concepts, we can train our structure in an end-to-end supervised fashion on a collection of sketch-image pairs. The generated sketches of our architecture can be classified with 85.6% Top-5 accuracy and we verify their visual quality via a user study. We find that deep features as a perceptual similarity metric enable image translation with large domain gaps and our findings further show that convolutional neural networks trained on image classification tasks implicitly learn to encode shape information.

Bibtex:
```
@inproceedings{kampelmuehler2020synthesizing,
  title={Synthesizing human-like sketches from natural images using a conditional convolutional decoder},
  author={Kampelm{\"u}hler, Moritz and Pinz, Axel},
  booktitle={2020 IEEE Winter Conference on Applications of Computer Vision (WACV)},
  year={2020},
  organization={IEEE}
}
```

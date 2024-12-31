# Magic Mirror: ID-Preserved Video Generation in Video Diffusion Transformers



<img style="margin: 20 auto; height: 140px; display: block;" src="assets/logo.png" > 

<p align="center">
<a href='https://julianjuaner.github.io/projects/MagicMirror/'><img src='https://img.shields.io/badge/project_page-aa55dd'></a>
<a href='https://arxiv.org/abs/2312.04302'><img src='https://img.shields.io/badge/arXiv_paper-ee7744'></a>
</p>

| Reference Image | Generated Video | Generated Video |
| ---- | ---- | ---- |
| <img height="240px" src="assets/teaser_6.png" > | <video height="240" controls autoplay><source src="assets/teaser_6_1.mp4" type="video/mp4"></video> | <video height="240" controls autoplay><source src="assets/teaser_6_2.mp4" type="video/mp4"></video> |
| <img height="240px" src="assets/teaser_5.png"> | <video height="240" controls autoplay><source src="assets/teaser_5_1.mp4" type="video/mp4"></video> | <video height="240" controls autoplay><source src="assets/teaser_5_2.mp4" type="video/mp4"></video> |
| <img height="240px" src="assets/teaser_4.png"> | <video height="240" controls autoplay><source src="assets/teaser_4_1.mp4" type="video/mp4"></video> | <video height="240" controls autoplay><source src="assets/teaser_4_2.mp4" type="video/mp4"></video> |
| <img height="240px" src="assets/teaser_1.png"> | <video height="240" controls autoplay><source src="assets/teaser_1_1.mp4" type="video/mp4"></video> | <video height="240" controls autoplay><source src="assets/teaser_1_2.mp4" type="video/mp4"></video> |

## Overview

- [Magic Mirror: ID-Preserved Video Generation in Video Diffusion Transformers](#magic-mirror-id-preserved-video-generation-in-video-diffusion-transformers)
  - [Overview](#overview)
  - [MileStones](#milestones)
  - [Methods](#methods)
  - [Cite Magic Mirror](#cite-magic-mirror)

## MileStones

* [X] `20250101` Paper released!
* [ ] `202501-202502` We will release code and model (we are working on fit our methods on CogVideoX-1.5, HunyuanVideo, .etc). Stay tuned!

## Methods
![framework](assets/framework.png)

In this work, we presented Magic Mirror, a zero-shot framework for identity-preserved video generation. Magic Mirror incorporates dual facial embeddings and Conditional Adaptive Normalization (CAN) into DiT-based architectures. Our approach enables robust identity preservation and stable training convergence. Extensive experiments demonstrate that Magic Mirror generates high-quality personalized videos while maintaining identity consistency from a single reference image, outperforming existing methods across multiple benchmarks and human evaluations. 

## Cite Magic Mirror

If you find this repo useful for your research, please consider citing the paper

```bibtex
@inproceedings{zhang2025magic,
  title={Magic Mirror: ID-Preserved Video Generation in Video Diffusion Transformers},
  author={Zhang, Yuechen and Yaoyang, Liu and Bin, Xia and Bohao, Peng and Zexin, Yan and Eric, Lo and Jiaya, Jia}
}
```

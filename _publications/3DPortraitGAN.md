---
title: "3DPortraitGAN: Learning Canonical Full-Head 3D GANs from a Single-View Portrait Dataset with Diverse Body Poses"
collection: publications
permalink: /publication/3DPortraitGAN
excerpt: '**Yiqian Wu**, [Hao Xu](https://xh38.github.io/), [Xiangjun Tang](https://yuyujunjun.github.io/), [Hongbo Fu](http://sweb.cityu.edu.hk/hongbofu/publications.html), [Xiaogang Jin*](http://www.cad.zju.edu.cn/home/jin)'
date: 2023-08-22
venue: 'Preprints'
paperurl: 'https://arxiv.org/abs/2307.14770'
citation: 'http://oneThousand1000.github.io/files/bibtex/3DPortraitGAN.html'
code: 'https://github.com/oneThousand1000/3DPortraitGAN'
video: 'coming soon'
supplementary_materials: 'https://drive.google.com/file/d/16aNE5USZ0U32bgGJS1G5xWrY0oIMTfre/view?usp=sharing'
project_page: 'https://github.com/oneThousand1000/3DPortraitGAN'
year: '2023'
---
![coarse2fine](http://oneThousand1000.github.io/images/publications/3DPortraitGAN.png)

<b>Abstract:</b>

3D-aware face generators are typically trained on 2D real-life face image datasets that primarily consist of near-frontal face data, and as such, they are unable to construct [one-quarter headshot](https://www.backstage.com/magazine/article/types-of-headshots-75557/) 3D portraits with complete head, neck, and shoulder geometry. Two reasons account for this issue: First, existing facial recognition methods struggle with extracting facial data captured from large camera angles or back views. Second, it is challenging to learn a distribution of 3D portraits covering the one-quarter headshot region from single-view data due to significant geometric deformation caused by diverse body poses. To this end, we first create the dataset 360°-Portrait-HQ (360°PHQ for short) which consists of high-quality single-view real portraits annotated with a variety of camera parameters (the yaw angles span the entire 360° range) and body poses. We then propose 3DPortraitGAN, the first 3D-aware one-quarter headshot portrait generator that learns a canonical 3D avatar distribution from the 360°PHQ dataset with body pose self-learning. Our model can generate view-consistent portrait images from all camera angles with a canonical one-quarter headshot 3D representation. Our experiments show that the proposed framework can accurately predict portrait body poses and generate view-consistent, realistic portrait images with complete geometry from all camera angles.  

[Paper](https://arxiv.org/abs/2307.14770) 

[Suppl](https://drive.google.com/file/d/16aNE5USZ0U32bgGJS1G5xWrY0oIMTfre/view?usp=sharing) 

[Project Page](https://github.com/oneThousand1000/3DPortraitGAN)



Recommended citation: 
```
@misc{wu20233dportraitgan,
      title={3DPortraitGAN: Learning One-Quarter Headshot 3D GANs from a Single-View Portrait Dataset with Diverse Body Poses}, 
      author={Yiqian Wu and Hao Xu and Xiangjun Tang and Hongbo Fu and Xiaogang Jin},
      year={2023},
      eprint={2307.14770},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```

---
title: "LPFF: A Portrait Dataset for Face Generators Across Large Poses"
collection: publications
permalink: /publication/lpff-dataset
excerpt: '[**Yiqian Wu**](https://onethousandwu.com/), Jing Zhang, [Hongbo Fu](http://sweb.cityu.edu.hk/hongbofu/publications.html), [Xiaogang Jin](http://www.cad.zju.edu.cn/home/jin)'
date: 2023-08-30
venue: 'Arxiv'
paperurl: 'https://arxiv.org/abs/2303.14407'
citation: 'http://oneThousand1000.github.io/files/bibtex/lpff.html'
code: 'https://github.com/oneThousand1000/LPFF-dataset'
video: 'coming soon'
supplementary_materials: 'https://drive.google.com/file/d/1Xktg7oqMMNN9hqGYva3BBTJoux17y2SR/view?usp=sharing'
project_page: 'https://github.com/oneThousand1000/LPFF-dataset'
year: '2023'
---
![coarse2fine](http://oneThousand1000.github.io/images/publications/lpff.png)

<b>Abstract:</b>

The creation of 2D realistic facial images and 3D face shapes using generative networks has been a hot topic in recent years. Existing face generators exhibit exceptional performance on faces in small to medium poses (with respect to frontal faces), but struggle to produce realistic results for large poses. The distorted rendering results on large poses in 3D-aware generators further show that the generated 3D face shapes are far from the distribution of 3D faces in reality. We find that the above issues are caused by the training dataset's posture imbalance.

In this paper, we present **LPFF**, a large-pose Flickr face dataset comprised of 19,590 high-quality real large-pose portrait images. We utilize our dataset to train a 2D face generator that can process large-pose face images, as well as a 3D-aware generator that can generate realistic human face geometry. To better validate our pose-conditional 3D-aware generators, we develop a new FID measure to evaluate the 3D-level performance. Through this novel FID measure and other experiments, we show that LPFF can help 2D face generators extend their latent space and better manipulate the large-pose data, and help 3D-aware face generators achieve better view consistency and more realistic 3D reconstruction results.



[Paper](https://arxiv.org/abs/2303.14407) 

[Video](coming soon) 

[Suppl](https://drive.google.com/file/d/1Xktg7oqMMNN9hqGYva3BBTJoux17y2SR/view?usp=sharing) 

[Project Page](coming soon)



Recommended citation: 
```
@misc{wu2023lpff,
      title={LPFF: A Portrait Dataset for Face Generators Across Large Poses}, 
      author={Yiqian Wu and Jing Zhang and Hongbo Fu and Xiaogang Jin},
      year={2023},
      eprint={2303.14407},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```

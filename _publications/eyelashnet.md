---
title: "EyelashNet: A Dataset and A Baseline Method for Eyelash Matting"
collection: publications
permalink: /publication/eyelashnet
excerpt: 'Qinjie Xiao, Hanyuan Zhang, Zhaorui Zhang, **Yiqian Wu**, Luyuan Wang, [Xiaogang Jin](http://www.cad.zju.edu.cn/home/jin/), Xinwei Jiang, [Yongliang Yang](https://www.yongliangyang.net/),  [Tianjia Shao](http://tianjiashao.com/), [Kun Zhou](http://kunzhou.net/).'
date: 2021-12-30
venue: 'ACM Trans. Graph., Vol. 40, No. 6, Article 217. Publication date: December 2021.'
paperurl: 'http://www.cad.zju.edu.cn/home/jin/siga2021/EyelashNet.pdf'
citation: ''
code: 'Coming Soon'
video: 'http://www.cad.zju.edu.cn/home/jin/siga2021/demo.mp4'
supplementary_materials: ''
project_page: 'http://www.cad.zju.edu.cn/home/jin/siga2021/siga2021.htm'
---

<b>Abstract:</b>

Eyelashes play a crucial part in the human facial structure and largely affect the facial attractiveness in modern cosmetic design. However, the appearance and structure of eyelashes can easily induce severe artifacts in high-fidelity multi-view 3D face reconstruction. Unfortunately it is highly challenging to remove eyelashes from portrait images using both traditional and learning based matting methods due to the delicate nature of eyelashes and the lack of eyelash matting dataset. To this end, we present EyelashNet, the first eyelash matting dataset which contains 5,400 high-quality eyelash matting data captured from real world and 5,272 virtual eyelash matting data created by rendering avatars. Our work consists of a capture stage and an inference stage to automatically capture and annotate eyelashes instead of tedious manual efforts. The capture is based on a specifically-designed fluorescent labeling system. By coloring the eyelashes with a safe and invisible fluorescent substance, our system takes paired photos with colored and normal eyelashes by turning the equipped ultraviolet (UVA) flashlight on and off. We further correct the alignment between each pair of photos and use a trained matting network to extract the eyelash alpha matte. As there is no prior eyelash dataset, we propose a progressive training strategy that progressively fuses captured eyelash data with virtual eyelash data to learn the latent semantics of real eyelashes. As a result, our method can accurately extract eyelash alpha mattes from fuzzy and self-shadow regions such as pupils, which is almost impossible by manual annotations. To validate the advantage of EyelashNet, we present a baseline method based on deep learning that achieves state-of-the-art eyelash matting performance with RGB portrait images as input. We also demonstrate that our work can largely benefit important real applications including high-fidelity personalized avatar and cosmetic design.

[[paper](http://www.cad.zju.edu.cn/home/jin/siga2021/EyelashNet.pdf)]  

[[demo](http://www.cad.zju.edu.cn/home/jin/siga2021/demo.mp4)]  

[[code]()]  coming soon.

[[project page](http://www.cad.zju.edu.cn/home/jin/siga2021/siga2021.htm)]

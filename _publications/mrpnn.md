---
title: "Deep Real-time Volumetric Rendering Using Multi-feature Fusion"
collection: publications
permalink: /publication/mrpnn
excerpt: 'Jinkai Hu, Chengzhong Yu, Hongli Liu, [Ling-qi Yan](https://sites.cs.ucsb.edu/~lingqi/index.html), **Yiqian Wu**, [Xiaogang Jin](http://www.cad.zju.edu.cn/home/jin)'
date: 2023-08-30
venue: "Proceedings of Siggraph'2023, Los Angeles, 6-10 August."
paperurl: 'https://sites.cs.ucsb.edu/~lingqi/publications/paper_mrpnn.pdf'
citation: 'coming soon'
code: 'https://github.com/What-a-stupid-username/MRPNN'
video: 'http://www.cad.zju.edu.cn/home/jin/sig20231/demo.mp4'
supplementary_materials: 'http://www.cad.zju.edu.cn/home/jin/sig20231/Supplementary.pdf'
project_page: 'http://www.cad.zju.edu.cn/home/jin/sig20231/SigMRPNN2023.htm'
year: '2023'
---
![mrpnn](http://oneThousand1000.github.io/images/publications/mrpnn.png)

<b>Abstract:</b>

We present Multi-feature Radiance-Predicting Neural Networks (MRPNN), a practical framework with a lightweight feature fusion neural network for rendering high-order scattered radiance of participating media in real time. By reformulating the Radiative Transfer Equation (RTE) through theoretical examination, we propose **transmittance fields**, generated at a low cost, as auxiliary information to help the network better approximate the RTE, drastically reducing the size of the neural network. The light weight network efficiently estimates the difficult-to-solve in-scattering term and allows for configurable shading parameters while improving prediction accuracy. In addition, we propose a frequency-sensitive stencil design in order to handle non-cloud shapes, resulting in accurate shadow boundaries. Results show that our MRPNN is able to synthesize indistinguishable output compared to the ground truth. Most importantly, MRPNN achieves a speedup of two orders of magnitude compared to the state-of-the-art, and is able to render high-quality participating material in real time.

[Paper](https://sites.cs.ucsb.edu/~lingqi/publications/paper_mrpnn.pdf) 

[Video](http://www.cad.zju.edu.cn/home/jin/sig20231/demo.mp4) 

[Suppl](http://www.cad.zju.edu.cn/home/jin/sig20231/Supplementary.pdf) 

[Project Page]([Deep Real-time Volumetric Rendering Using Multi-feature Fusion (zju.edu.cn)](http://www.cad.zju.edu.cn/home/jin/sig20231/SigMRPNN2023.htm))



Recommended citation: 
```
coming soon
```

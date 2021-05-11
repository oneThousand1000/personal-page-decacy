---
title: "Coarse-to-Fine: Facial Structure Editing of Portrait Images via Latent Space Classifications"
collection: publications
permalink: /publication/coarse-to-fine
excerpt: '**Yiqian Wu**, [Yongliang Yang](https://www.yongliangyang.net/), Qinjie Xiao, [Xiaogang Jin](http://www.cad.zju.edu.cn/home/jin/).'
date: 2021-08-30
venue: 'ACM Transactions on Graphics (Proc. of Siggraph 2021), 40(4): Article 46.'
paperurl: 'paper url is coming soon'
citation: 'coming soon'
code: 'https://github.com/oneThousand1000/coarse-to-fine-chin-editing'
video: 'coming soon'
---
![coarse2fine](http://oneThousand1000.github.io/images/publications/coarse2fine.png)

<b>Abstract:</b>

Facial structure editing of portrait images is challenging given the facial variety, the lack of ground-truth, the necessity of jointly adjusting color and shape, and the requirement of no visual artifacts. In this paper, we investigate how to perform chin editing as a case study of editing facial structures. We present a novel method that can automatically remove the double chin effect in portrait images. Our core idea is to train a fine classification boundary in the latent space of the portrait images. This can be used to edit the chin appearance by manipulating the latent code of the input portrait image while preserving the original portrait features. To achieve such a fine separation boundary, we employ a carefully designed training stage based on latent codes of paired synthetic images with and without a double chin. In the testing stage, our method can automatically handle portrait images with only a refinement to subtle misalignment before and after double chin editing. Our model enables alteration to the neck region of the input portrait image while keeping other regions unchanged, and guarantees the rationality of neck structure and the consistency of facial characteristics. To the best of our knowledge, this presents the first effort towards an effective application for editing double chins. We validate the efficacy and efficiency of our approach through extensive experiments and user studies.

[[paper(high resolution)](https://drive.google.com/file/d/14w9j2w8EoeH7ikD9aljT7JfulPPsvky4/view?usp=sharing)]  

[[paper(low resolution)](https://drive.google.com/file/d/1Kk--kQdCB91QgkmrmOV2OwsoeF05vLr5/view?usp=sharing)]  

[[demo](https://drive.google.com/file/d/1vaohqZ_GqgydIpnVpPv_K-7bl_UW6IyG/view?usp=sharing)]  

[[code]()]  coming soon.

[[supplementary materials](https://drive.google.com/file/d/14oIdiv2NkvpRYxomDRq0AQEpBuL4pKtv/view?usp=sharing)]

[[project page](http://www.cad.zju.edu.cn/home/jin/sig2021/sig2021.htm)]

[[dataset]](https://github.com/oneThousand1000/coarse-to-fine-chin-editing)

Recommended citation: Yiqian Wu, Yong-Liang Yang, Qinjie Xiao, and Xiaogang Jin. 2021. Coarse-to-Fine: Facial Structure Editing of Portrait Images via Latent Space Clas-sifications.ACM Trans. Graph.40, 4, Article 46 (August 2021), 13 pages. https://doi.org/10.1145/3450626.3459

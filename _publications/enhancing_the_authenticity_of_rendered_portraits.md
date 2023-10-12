---
title: "Enhancing the Authenticity of Rendered Portraits with Identity-Consistent Transfer Learning"
collection: publications
permalink: /publication/enhancing_the_authenticity_of_rendered_portraits
excerpt: 'Luyuan Wang*, **Yiqian Wu\*** (\*Equal Contribution), [Yongliang Yang](https://www.yongliangyang.net/), Chen Liu, [Xiaogang Jin](http://www.cad.zju.edu.cn/home/jin/).'
date: 2023-10-06
venue: 'Preprints'
paperurl: 'https://arxiv.org/abs/2310.04194'
citation: 'http://oneThousand1000.github.io/files/bibtex/enhancing_the_authenticity_of_rendered_portraits.html'
code: 'coming soon'
video: 'coming soon'
supplementary_materials: 'coming soon'
project_page: 'coming soon'
year: '2023'
first_author: 'no'
---
![enhancing_the_authenticity_of_rendered_portraits](http://oneThousand1000.github.io/images/publications/enhancing_the_authenticity_of_rendered_portraits.png)

<b>Abstract:</b>

Despite rapid advances in computer graphics, creating high-quality photo-realistic virtual portraits is prohibitively expensive. Furthermore, the well-known ''uncanny valley'' effect in rendered portraits has a significant impact on the user experience, especially when the depiction closely resembles a human likeness, where any minor artifacts can evoke feelings of eeriness and repulsiveness. In this paper, we present a novel photo-realistic portrait generation framework that can effectively mitigate the ''uncanny valley'' effect and improve the overall authenticity of rendered portraits. Our key idea is to employ transfer learning to learn an identity-consistent mapping from the latent space of rendered portraits to that of real portraits. During the inference stage, the input portrait of an avatar can be directly transferred to a realistic portrait by changing its appearance style while maintaining the facial identity. To this end, we collect a new dataset, **D**az-**R**endered-**F**aces-**HQ** (**DRFHQ**), that is specifically designed for rendering-style portraits. We leverage this dataset to fine-tune the StyleGAN2 generator, using our carefully crafted framework, which helps to preserve the geometric and color features relevant to facial identity. We evaluate our framework using portraits with diverse gender, age, and race variations. Qualitative and quantitative evaluations and ablation studies show the advantages of our method compared to state-of-the-art approaches.



[Paper](https://arxiv.org/abs/2310.04194) 

[Video](coming soon) 

[Suppl](coming soon) 

[Project Page](coming soon)



Recommended citation: 
```
@misc{wang2023enhancing,
      title={Enhancing the Authenticity of Rendered Portraits with Identity-Consistent Transfer Learning}, 
      author={Luyuan Wang and Yiqian Wu and Yongliang Yang and Chen Liu and Xiaogang Jin},
      year={2023},
      eprint={2310.04194},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```
# EVALUATION3 Dataset


🖤 **Download**

🍒 [[DOWNLOAD]]()

🖤 **Brief Intro**

This is a outfit dataset. The orginal source of outfits are collected from [PolyVore](https://github.com/xthan/polyvore-dataset) and [FashionVC](https://github.com/SDU-MIMA/SHDCH). Different from the previous outfit datasets, we annotated the outfit with evaluation labels as Good, Normal, and Bad. Additionally, we labeled the attributes of all the fashion items.

![图片5.png](https://i.loli.net/2021/06/25/1peogM8JbR9skIm.png)

This means that the EVALUATION3 dataset contains the evaluation labels (good, normal, bad) and its related reasons (color, print, material, silhouette, and designs) attributes labels of each fashion items (including Top(U), bottom(B), bag(G), and shoes(S)). We summary the details of EVALUATION3 in the following Table:

|  - | Outfits | Shoes | Bags | Attribute value of Top |   Attribute value of Bottom | Attribute value of Bags | Attribute value of Shoes | Evaluation | Reason |
|:---------:|:-------:|:-------:|:-------:|:--------:|:------:|:------:|:--------:|:------:|:--------:|
| Numbers  | 34,479 | 24,387 | 24,282 | 82  |   45 |   42 |   47 | 3 |   5 |

To better demonstrate the attributes labeled in this dataset, we here take shoes as an example. Followed the logic adopted in FashionAI, we first identify the characteristics (attribute dimension) of distinguishing shoes. For example, Heel Height, Heel Type, Toe Box, etc. Then, we investigate the different designs in each attribute dimension and carefully define the attribute values.

![图片10.jpg](https://i.loli.net/2021/06/25/svfzoalBV3L6mrT.jpg)

After unzipping the file, you are expected to obtain fashion data like this below:

![图片11.png](https://i.loli.net/2021/06/25/LpzUrsR6TZklQve.png)

Please cite the following reference paper when this dataset is used in any academic and research reports.

🖤 **Reference**

**Regularizing Reasons for Outfit Evaluation with Gradient Penalty** [[pdf]](https://arxiv.org/pdf/2002.00460v1.pdf)

```bib
@article{zou2020regularizing,
  title={Regularizing Reasons for Outfit Evaluation with Gradient Penalty},
  author={Zou, Xingxing and Li, Zhizhong and Bai, Ke and Lin, Dahua and Wong, Waikeung},
  journal={arXiv preprint arXiv:2002.00460},
  year={2020}
}
```

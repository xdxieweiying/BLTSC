# Background-Learning-Based-on-Target-Suppression-Constraint-for-Hyperspectral-Target-Detection# ReadMe
**Abstract：** <br />
Hyperspectral target detection is critical in both military and civilian applications. However, it is a challenging task due to the complexity of background and the limited samples of target in hyperspectral images (HSIs). In this article, we propose a novel background learning model, called background learning based on target suppression constraint to characterize high-dimensional spectral vectors. Considering insufficient target samples, the model is trained only on the background spectral samples to accurately learn the background distribution. Then the discrepancy between the reconstructed and original HSIs are examined to spot the targets. To obtain a background training dataset, coarse detection is carried out. However, it is quite difficult to retrieve pure background data. Thus, a target suppression constraint is imposed to reduce the impact of suspected target samples on background reconstruction. Experiments on six real HSIs demonstrate that the proposed framework significantly outperforms the current state-of-the-art detection methods and yields higher detection accuracy and lower false alarm rate. <br />
**Code & Model:** https://github.com/zhangxin-xd/BLTSC <br />
**Paper:** https://doi.org/10.1109/JSTARS.2020.3024903
<br />
If our code is helpful to you, please cite:
```
@ARTICLE{9200776,
  author={Xie, Weiying and Zhang, Xin and Li, Yunsong and Wang, Keyan and Du, Qian},
  journal={IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing}, 
  title={Background Learning Based on Target Suppression Constraint for Hyperspectral Target Detection}, 
  year={2020},
  volume={13},
  number={},
  pages={5887-5897},
  doi={10.1109/JSTARS.2020.3024903}}

```

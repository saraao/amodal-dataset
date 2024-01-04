# Amodal Intra-class Instance Segmentation: Synthetic Datasets and Benchmark [WACV 2024]

Jiayang Ao,  Qiuhong Ke, Krista A. Ehinger

[ArXiv](https://arxiv.org/abs/2303.06596)&nbsp;&nbsp;&nbsp;&nbsp;[Datasets](https://forms.office.com/r/diADGWuLA5)

# Introduction of the Datasets
This repository has released the datasets for the paper "Amodal Intra-class Instance Segmentation: Synthetic Dataset and Benchmark" (WACV 2024), which includes:
<li> <b> Intra-AFruit</b>, an intra-class occlusion synthetic dataset containing 10 classes of fruits and vegetables, with 210,000 images for training and 45,000 images for
testing.</li>
<li> <b> ACom</b>, an intra-class occlusion synthetic dataset containing 10 classes of other common object categories (anise, biscuit, bottle, candy, conch,
donut, fire extinguisher, hammer, hat, and toothpaste), with 10,000 images for training and 2,500 images for
testing. </li>
<br>
We additionally created two datasets for testing purposes:
<li> <b>InterAMix</b>, which considers occlusion scenes of multiple categories of objects by randomly picking instances among all categories.</li> 
<li> <b> A real-world image dataset</b>, of intra-class occlusion scenes containing 102 images.</li>
<br>
<img width="800" alt="Example Images" src="https://github.com/saraao/amodal-dataset/assets/39376629/f3295032-d539-45d6-b96a-b3b7831298eb">

Example Images from our datasets: Intra-AFruit, InterAMix, ACom, and Real Images (ordered from left to right with two examples per column for each dataset). The annotation format follows COCO style. 

# Citation
If you find this useful in your work, please consider citing the following reference:
```
@inproceedings{ao2024amodal,
  title={Amodal Intra-Class Instance Segmentation: Synthetic Datasets and Benchmark},
  author={Ao, Jiayang and Ke, Qiuhong and Ehinger, Krista A},
  booktitle={Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision},
  pages={281--290},
  year={2024}
}
```

# Contact
If you have any questions regarding this work, please send email to jiayang.ao@student.unimelb.edu.au.

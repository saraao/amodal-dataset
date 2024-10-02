# Amodal Intra-class Instance Segmentation: Synthetic Datasets and Benchmark [WACV 2024]

<p align="center">
  <p align="center" margin-bottom="0px">
    <a href="https://jiayangao.github.io/"><strong>Jiayang Ao</strong></a>
    ·
    <a href="https://research.monash.edu/en/persons/qiuhong-ke/"><strong>Qiuhong Ke</strong></a>
    ·
    <a href="http://www.kehinger.com/"><strong>Krista A. Ehinger</strong></a>
    <p align="center">
    <a href="https://arxiv.org/abs/2303.06596" style="text-decoration:none;">
      <img src="https://img.shields.io/badge/arXiv-2303.06596-b31b1b.svg" alt="arXiv Badge">
    </a>
    <a href="https://openaccess.thecvf.com/content/WACV2024/papers/Ao_Amodal_Intra-Class_Instance_Segmentation_Synthetic_Datasets_and_Benchmark_WACV_2024_paper.pdf" style="text-decoration:none;">
      <img src="https://img.shields.io/badge/Pub-WACV'24-blue" alt="WACV Badge">
    </a>
    <a href="https://unimelbcloud-my.sharepoint.com/:f:/g/personal/jiayanga_student_unimelb_edu_au/EnJw4L6DwqtFs9URrdUKEuYBBsitZlqU-Vdd3H0fO55BWQ?e=dy8rNp" style="text-decoration:none;">
      <img src="https://img.shields.io/badge/Download-DATASETS-yellow" alt="DATASETS Badge">
    </a>
  </p>
</p>

# Abstract
Images of realistic scenes often contain intra-class objects that are heavily occluded from each other, making the amodal perception task that requires parsing the occluded parts of the objects challenging. Although important for downstream tasks such as robotic grasping systems, the lack of large-scale amodal datasets with detailed annotations makes it difficult to model intra-class occlusions explicitly. This paper introduces two new amodal datasets for image amodal completion tasks, which contain a total of over 267K images of intra-class occlusion scenarios, annotated with multiple masks, amodal bounding boxes, dual order relations and full appearance for instances and background. We also present a point-supervised scheme with layer priors for amodal instance segmentation specifically designed for intra-class occlusion scenarios. Experiments show that our weakly supervised approach outperforms the SOTA fully supervised methods, while our layer priors design exhibits remarkable performance improvements in the case of intra-class occlusion in both synthetic and real images.

# Introduction of the Datasets
This repository has released the datasets ([download here](https://unimelbcloud-my.sharepoint.com/:f:/g/personal/jiayanga_student_unimelb_edu_au/EnJw4L6DwqtFs9URrdUKEuYBBsitZlqU-Vdd3H0fO55BWQ?e=dy8rNp)) for the paper "Amodal Intra-class Instance Segmentation: Synthetic Dataset and Benchmark" (WACV 2024), which includes:
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

Example Images from our datasets: Intra-AFruit, InterAMix, ACom, and Real Images (ordered from left to right with two examples per column for each dataset). 
<br>



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

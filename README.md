# M3DeTR: Multi-representation, Multi-scale, Mutual-relation 3D Object Detection with Transformers

The code base for [M3DeTR: Multi-representation, Multi-scale, Mutual-relation 3D Object Detection with Transformers](https://openaccess.thecvf.com/content/WACV2022/html/Guan_M3DETR_Multi-Representation_Multi-Scale_Mutual-Relation_3D_Object_Detection_With_Transformers_WACV_2022_paper.html)
<br>**Tianrui Guan***, **Jun Wang***, Shiyi Lan, Rohan Chandra, Zuxuan Wu, Larry Davis, Dinesh Manocha


## Abstract
<div style="text-align: justify">We present a novel architecture for 3D object detection, M3DeTR, which combines different point cloud representations (raw, voxels, bird-eye view) with different feature scales based on multi-scale feature pyramids. M3DeTR is the first approach that unifies multiple point cloud representations, feature scales, as well as models mutual relationships between point clouds simultaneously using transformers. We perform extensive ablation experiments that highlight the benefits of fusing representation and scale, and modeling the relationships. Our method achieves state-of-the-art performance on the KITTI 3D object detection dataset and Waymo Open Dataset. Results show that M3DeTR improves the baseline significantly by 1.48% mAP for all classes on Waymo Open Dataset. In particular, our approach ranks 1st on the well-known KITTI 3D Detection Benchmark for both car and cyclist classes, and ranks 1st on Waymo Open Dataset with single frame point cloud input. </div>

<p>&nbsp;</p>

<img src="https://obj.umiacs.umd.edu/acmmm2021/coverpic-1.png" width="600">


### Features
* A unified architecture for 3D object detection with transformers that accounts for multi-representation, multi-scale, mutual-relation models of point clouds in an end-to-end manner.
* Support major 3D object detection datasets: Waymo Open Dataset, KITTI.

## Installation

See [installation instructions](INSTALL.md).

## Getting Started

See [Getting Started with M3DeTR](GETTING_STARTED.md).


## Model Zoo and Baselines

We provide a large set of baseline results and trained models available for download in the [M3DeTR Model Zoo](MODEL_ZOO.md).


## Citation
Please cite our work if you found it useful,

```
@InProceedings{Guan_2022_WACV,
    author    = {Guan, Tianrui and Wang, Jun and Lan, Shiyi and Chandra, Rohan and Wu, Zuxuan and Davis, Larry and Manocha, Dinesh},
    title     = {M3DETR: Multi-Representation, Multi-Scale, Mutual-Relation 3D Object Detection With Transformers},
    booktitle = {Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision (WACV)},
    month     = {January},
    year      = {2022},
    pages     = {772-782}
}
```
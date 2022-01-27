# 3D Object Detection: LIDAR Semantic Segmentation
Semantic segmentation of LIDAR point clouds from the [KITTI-360 dataset](http://www.cvlibs.net/datasets/kitti-360/) using a modified [PointNet2](https://github.com/charlesq34/pointnet2). This is a Python and PyTorch based implementation in a Jupyter Notebook. The following animation shows the model predictions by color.

<iframe width="560" height="315" src="https://www.youtube.com/embed/wxTNgwHcsbE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


# Abstract
This project proposes and implements a new variant of [PointNet2](https://github.com/charlesq34/pointnet2) architecture for semantic segmentation of point clouds. The main difference between this implementation and the original one is the methodology for choosing and processing local features. Here I propose an alternative to the farthest point sampling (FPS) algorithm that improves accuracy by roughly 3 percent.


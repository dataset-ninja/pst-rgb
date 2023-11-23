**PST-RGB: Penn Subterranean Thermal RGB Dataset** is a dataset for instance segmentation, semantic segmentation, and object detection tasks. It is used in the robotics industry. 

The dataset consists of 3359 images with 3936 labeled objects belonging to 4 different classes including *backpack*, *fire extinguisher*, *rescue randy*, and other: *hand drill*.

Images in the PST-RGB dataset have pixel-level instance segmentation annotations. Due to the nature of the instance segmentation task, it can be automatically transformed into a semantic segmentation (only one mask for every class) or object detection (bounding boxes for every object) tasks. There are 887 (26% of the total) unlabeled images (i.e. without annotations). There are no pre-defined <i>train/val/test</i> splits in the dataset. The dataset was released in 2020 by the University of Pennsylvania, USA.

Here are the visualized examples for the classes:

[Dataset classes](https://github.com/dataset-ninja/pst-rgb/raw/main/visualizations/classes_preview.webm)

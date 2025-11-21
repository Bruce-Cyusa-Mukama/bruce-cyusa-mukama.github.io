---
profile:
  align: right
  image: msca.jpg
  image_circular: false # crops the image to make it circular
  more_info: >
    <p> Curriculum semi-supervised segmentation of medical images via predicted bounding boxes</p>
---

This is my 2021 master thesis. It is written in french, but I also contains an english-translated abstract:
"Although deep learning has nowadays become the de facto solution for medical image segmentation, one the limitations that remain is the need of large labelled dataset for training, which are hard to obtain. This research proposes a new semi-supervised training strategy, to alleviate the annotation burden. Our focus consists in exploiting domain knowledge, about the organ of interest, to constrain directly the predicted segmentations. Specifically, we exploit unlabeled images, in a semisupervised curriculum context, by using an auxiliary neural network to predict the bounding boxes of the organs that unlabeled images may contain. These predicted bounding boxes are then used to constrain the size, the global location and the topology of the corresponding predicted segmentations. We present extensive experiments to showcase the benefits of the proposed methodology. In particular, the reported results demonstrate that by including our constrained formulation, a performance gain ranging from 0.3 to 4.4% is obtained compared to the fully supervised counterpart (in terms of Sorensen-Dice coefficient), when the same amount of annotations is used. These results are consistent across two different medical segmentation datasets, i.e., left-ventricle and prostate, which demonstrates the generalizability of our approach. Among our recommendations, we advocate a more extensive study that uses a standard detection architecture (region based convolutional neural networks, single-shot detectors, etc.), to better access the extent of this supervision’s performance."

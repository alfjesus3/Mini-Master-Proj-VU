# Mini-Master-Proj-VU
For a Research course at VU in the thesis preparation.

## Report Abstract
Current convolutional based object detectors lack generalization capabilities. Using a custom feature extractor architecture tailored for a target type of detection task appears as a more flexible and efficient alternative. Recent developments in neural architecture search (NAS) have enabled methods like DetNAS to provide a custom object detection feature extractor. It is a first step towards applying Meta-Learning approaches in underwater object detection. In experiments, it is shown by comparing to other methods, that DetNAS achieves comparable performance. Despite this, the inference speed gain is not verified which limits the reachability of the approach. In cases when limited data is available, such as labelled underwater scenes, a bigger effort should be laid on improving the data quality and exploring semi-supervised training approaches. The code for the experiments is available at https://github.com/alfjesus3/Mini-Master-Proj-VU.

The report can be viewed at (TODO).

## Experimental Setup
* In order to apply DetNAS to the underwater datasets, the original authors' repository was used (https://github.com/megvii-model/DetNAS). 
  * Some adaptations were made in order to use the new datasets - DetNAS/maskrcnn_benchmark/config/paths_catalog.py and DetNAS/maskrcnn_benchmark/data/datasets/ .
  *  Since DetNAS is based on mask_rcnn_benchmark the following tutorial was helpful (https://github.com/facebookresearch/maskrcnn-benchmark/issues/521)
* For the Resnet18 experimentation, the Detectron2 library was used with some adjustments for the underwater datasets. The documentation for Custom datasets was used (https://detectron2.readthedocs.io/en/latest/tutorials/datasets.html).
* The Brackish dataset can be found in Kaggle (https://www.kaggle.com/aalborguniversity/brackish-dataset)
* The Urpc 2019 version is available at (http://www.cnurpc.org/a/js/2019/0805/125.html)
* My implementation of the experiments can be made available upon request.

## Hardware for Experiments
* In the following experiments, a multi-GPU computing setup with SSD was used to reduced the computation time required to train the models. For stage 1 and stage 2 of DetNAS, Nvidia Titan X with 12 GB of VRAM were used; the same is used for the Resnet18 models. Regarding stage 3 of DetNAS, the Nvidia RTX 2080 TI were used with 11 GB of VRAM. 

## Results
* The detection visual results for Brackish and Urpc 2019 are displayed on the ./Results/ folders. They are taken from Test samples on those datasets.

### References
* DetNAS: Backbone Search for Object Detection, Chen et. al. - ([http://arxiv.org/abs/1802.05983])
[http://arxiv.org/abs/1802.05983]: http://arxiv.org/abs/1802.05983

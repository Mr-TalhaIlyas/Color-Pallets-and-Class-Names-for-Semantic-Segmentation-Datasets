[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2FMr-TalhaIlyas%2FColor-Pallets-and-Class-Names-for-Semantic-Segmentation-Datasets&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false)](https://hits.seeyoufarm.com)
# Class Names and Color Pallets for Segmentation Datasets

There are a number of public datasets avalilable for testing your semantic segementatio models. Each data set is unique and has its own challenages, problems and complexity level.
Each data represents different scenarios of real life like autonomous driving, person body part, common objects etc. 

Usually the list of calss names and particularly the **color pallet** is not provided wiht the dataset so I collected the names of classes and their corresponding color pallets and added in this repo.
you can use them to color your results.

## Semantic Segmentation

Simply put semantic segmentation is a dense classification problem in which the CNN are supposed to classify each pixel of the input image w.r.t its corresponding class.

## Popular Dataset

Some of the popular datasets are given below you can also follow the link to download them (you might have to register wiht your work email first.)

* [Cityscape](https://www.cityscapes-dataset.com/downloads/)
* [Vistas](https://www.mapillary.com/dataset/vistas?pKey=1GyeWFxH_NPIQwgl0onILw&lat=20&lng=0&z=1.5)
* [ADE20k](https://groups.csail.mit.edu/vision/datasets/ADE20K/)
* [LIP](http://sysu-hcp.net/lip/)
* [COCO](https://cocodataset.org/#download)
* [Pascal VOC](http://host.robots.ox.ac.uk/pascal/VOC/)

## Panoptic Segmentation

If you wanna do **panoptic (semantic +  instance) segmenation**, then you will also need a list of *stuff* and *things* classes like in case of vistas and cityscape so I have also provided them inside the scripts.
Although a lot of semantic segmentation datasets also have their panoptic varients like cityscape, vistas etc. Here I'd like to mention the one I have worked on for panoptic segmentation.

* [PanNuke dataset](https://warwick.ac.uk/fac/cross_fac/tia/data/pannuke)

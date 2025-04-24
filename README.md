# MVPOD: A Multi-Vertical Perspective Object Detection Dataset

## Introduction

The MVPOD dataset contains **1,0470** images covering **8** object categories (including airplane, car, bus, truck, carrier, cargoship, warship and bridge). In terms of data annotation, MVPOD provides **horizontal** and **oriented** bounding boxes, and innovative vertical perspective labels for each object, covering common perspectives (nadir-downward, oblique-downward, and horizontal) as well as less common viewpoints (oblique-upward and nadir-upward).
<img src="https://github.com/iskiku/MVPOD/blob/main/demo.png"/>
You can use the MVPOD dataset to study object detection algorithms or rotated object detection algorithms. You can also study the variations in object detection performance under different vertical perspectives .

### Dataset Features

- ✅ Data diversity. The MVPOD dataset contains remote sensing images, drone images, and near-ground images. These data cover different shooting heights, providing rich scene information and visual features for object recognition tasks.
- ✅ Annotation diversity. The MVPOD dataset not only contains horizontal bounding box annotation information and rotated  bounding box annotation information, but also innovatively annotates the vertical perspective information of the object.
- ✅ High inter-class similarity and intra-class diversity. This is reflected in the rich object category selection of the MVPOD dataset.

## Download

You can download the dataset from the [Google Driver Link](https://drive.google.com/file/d/149Fo2hfIQ-O3uzeebLEMEAIAEYMvVKvd/view?usp=sharing).

> ⚠️ If the link is invalid or expired, feel free to open an issue or contact us!

## Directory Structure

After unzipping, the dataset directory is organized as follows:
```none
MVPOD
├── train2017
├── val2017
├── test2017
├── annotations
│   ├── instances_train2017.json
│   ├── instances_val2017.json
│   ├── instances_test2017.json
├── perspectives
│   ├── nadir-downward.txt
│   ├── oblique-downward.txt
│   ├── horizontal.txt
│   ├── oblique-upward.txt
│   ├── nadir-upward.txt
```

## License

This dataset is released under the [MIT license](LICENSE). 
Please make sure to properly cite this dataset if you use it in your research.

## Citation

If you use this dataset in your work, please cite it as:

```bibtex
@misc{MVPOD_Dataset,
  title     = {MVPOD},
  author    = {Haiyan Jin, Jintao Chen, Yuanlin Zhang},
  year      = {2025},
  url       = {https://github.com/iskiku/MVPOD}
}

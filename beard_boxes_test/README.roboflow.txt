
AIFaceAttribute - v9 2023-12-20 12:20am
==============================

This dataset was exported via roboflow.com on May 12, 2024 at 4:57 AM GMT

Roboflow is an end-to-end computer vision platform that helps you
* collaborate with your team on computer vision projects
* collect & organize images
* understand and search unstructured image data
* annotate, and create datasets
* export, train, and deploy computer vision models
* use active learning to improve your dataset over time

For state of the art Computer Vision training notebooks you can use with this dataset,
visit https://github.com/roboflow/notebooks

To find over 100k other datasets and pre-trained models, visit https://universe.roboflow.com

The dataset includes 11327 images.
Face_Attribute are annotated in Tensorflow Object Detection format.

The following pre-processing was applied to each image:
* Auto-orientation of pixel data (with EXIF-orientation stripping)
* Resize to 240x240 (Stretch)

The following augmentation was applied to create 3 versions of each source image:
* 50% probability of horizontal flip
* Randomly crop between 0 and 25 percent of the image
* Random shear of between -0° to +0° horizontally and -0° to +0° vertically

The following transformations were applied to the bounding boxes of each image:
* Random rotation of between -19 and +19 degrees
* Random exposure adjustment of between -15 and +15 percent
* Random Gaussian blur of between 0 and 1 pixels
* Salt and pepper noise was applied to 3 percent of pixels



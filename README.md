# Object-Detection-with-Custom-Dataset-from-Scratch
It is a repository that trains models with a special dataset using the Yolov9 architecture. This repository will be a guide where you can find everything you need for this model tutorial, with the library difficulties you may encounter during the installation phase and the necessary links.

## Steps to run in Colab
- Set runtime to t4
```
Selecting T4 GPU as the "Runtime" in Google Colab enables T4 GPUs to be used for GPU-accelerated computing. T4 is a graphics processor developed by NVIDIA and is very effective for training many deep learning and artificial intelligence models.
```
- Roboflow labeling tool
```
Roboflow is a platform for processing, tagging, and managing image and video data. It is designed to facilitate the data preparation process used especially for artificial intelligence projects such as computer vision, object detection, and image classification.
In this project, we labeled our dataset using Roboflow and integrated the code snippets into our project. Thanks to Roboflow's easy interface, we quickly processed our data set and made it ready for use. You can tag your own dataset automatically or manually using Roboflow's artificial intelligence tool in the project. You can get help from https://www.youtube.com/watch?v=lz_MITUBie8

```
- Train-Val-Test
```
Training: The model learns on the data set. It takes input data, predicts the target, and calculates an error by comparing it with the actual target. The error is used to update the internal parameters of the model.
Validation: Used to measure the generalization ability of the model. It contains data that is different from the training data but has similar characteristics. Validation error is monitored and training can be stopped.
Testing: Used to evaluate the real-world performance of the model. It contains data that the model has not seen before. Used to determine real-world performance.

```

```
For -->hyp.scratch-high.yaml
It represents the hyperparameter file that will be used during the training of the model.

wget https://github.com/ultralytics/yolov5/blob/master/data/hyps/hyp.scratch-high.yaml
```
## Steps to run in Local Environment
- Create enviorenment
```
conda create --name project
conda activate project

```
- Install Tensorflow
```
https://www.google.com/search?q=tensorflow+gpu+install&oq=tensorflow+gpu+&gs_lcrp=EgZjaHJvbWUqBwgBEAAYgAQyDAgAEEUYORiABBiiBDIHCAEQABiABDIHCAIQABiABDIHCAMQABiABDIHCAQQABiABDIHCAUQABiABDIHCAYQABiABDIHCAcQABiABDIHCAgQABiABDIKCAkQABiABBiiBNIBCDM4MDhqMGo3qAIAsAIA&sourceid=chrome&ie=UTF-8#fpstate=ive&vld=cid:1f47edd1,vid:EmZZsy7Ym-4,st:0

```
-Wget
```
https://www.google.com/search?q=tensorflow+gpu+install&oq=tensorflow+gpu+&gs_lcrp=EgZjaHJvbWUqBwgBEAAYgAQyDAgAEEUYORiABBiiBDIHCAEQABiABDIHCAIQABiABDIHCAMQABiABDIHCAQQABiABDIHCAUQABiABDIHCAYQABiABDIHCAcQABiABDIHCAgQABiABDIKCAkQABiABBiiBNIBCDM4MDhqMGo3qAIAsAIA&sourceid=chrome&ie=UTF-8#fpstate=ive&vld=cid:1f47edd1,vid:EmZZsy7Ym-4,st:0](https://www.youtube.com/watch?v=CkpTEJH6xkg

```
![output](https://github.com/kemaltekbas/YOLOv9-Object-Detection-with-Custom-Dataset-from-Scratch/assets/127952905/e9523207-7163-4618-93bf-fe8af9672eee)

## CREDIT
```
https://www.youtube.com/watch?v=XHT2c8jT3Bc&t=194s
https://github.com/SkalskiP/yolov9
https://app.roboflow.com/
```

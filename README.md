# Euro-Coin-Detection



### Overview : 
The purpose of this project is to create a Deep Learning model to detect the coin. My model is based on YOLO's object detection algorithm, and I'm using the dataset from Roboflow website.


### 📁 Dataset Used : From Roboflow Website
**The dataset consist of one class: Coin Detect**

 ![image](https://github.com/Tanwar-12/Euro-Coin-Detection/assets/110081008/3b9ea955-9c9f-4e25-8bce-ffe0e6fc9468)
# Workflow:
  ## Data Preparation:
  * Total 1017 images for training and 80 images for validation present in 1class.
  * Create a bounding boxes with the help of label-img And makesense.ai website according to YoloV5.
  * Prepare folder structure that can be accept by YoloV5.
  ![train folders](https://github.com/Tanwar-12/Face-Mask-Detection/assets/110081008/69b19a8e-2f81-4d9b-a762-ffa73ac59be1)
## Steps to use Yolov5:
* Cloning the YoloV5 file from official repository.
* Changing the directory of yolov5
* Installing the dependencies
* Download all versions pre-trained weights.

 ## Steps Before Training Custom Dataset:
* Go to yolov5/data/.
* Open data.yaml
* Edit the following inside it:
 1. Training and Validation file path
 2. Number of classes and Class names.

  ## Training YOLOV5 Model
* Set images size 640 with batch of 8.
* Train model around 300 epochs .
* Visualise the training metrics with the help of tensorboard.
* ## Testing Images Using Test Data
* ![image](https://github.com/Tanwar-12/Euro-Coin-Detection/assets/110081008/2cc3b326-9dd8-4c1c-98bf-a274ec861431)
* ![image](https://github.com/Tanwar-12/Euro-Coin-Detection/assets/110081008/466eaa65-e067-4e6b-8d74-1400bc99bcae)



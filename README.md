 # Yolov7-Object-Counter and custom functions 
* **Object Counting and custom functions with the newest yolov7**
* **Crop the bounding boxes**
 
 https://user-images.githubusercontent.com/77502485/196060371-e8d6b16f-b9ce-4f2f-bd4e-74bd68ce142e.mp4
 

 
 
 ### Ready to use tracking Google Colab file: https://colab.research.google.com/drive/1RK1IgQx6Fr7D2BwgCQJiUiZPclj69Myv?usp=sharing
 
 ### Update 1 (9/21/2022) a new model added for stock market predicion. Model file:https://drive.google.com/file/d/1_ud8ldVz1mnRU_Z3ygXEm0kWSjgSeOEW/view?usp=sharing
 * To detect: "stock_market_detect.py" file
 * Example video is below
 ### Update 2 (9/26/2022) a new file added for saving the images of bounding boxes file name: "save_bounding_boxes_images.py"
 * Example photo is below
 ### Update 3 (10/17/2022) a new file added for tracking and counting them. File name: "TRACK-SOURCE.py"
 
 
 https://user-images.githubusercontent.com/77502485/188005594-19cca6dd-6289-4cf0-94f2-d1c519d64949.mp4



 
 
### Please read first "README" before browsing the code
### Ready-to-use Google Colab file exists. you can copy this file and run it on your colab. File: https://colab.research.google.com/drive/1Bezq6IpAraT8Ee0v8flEJco6wsLn0T3I?usp=sharing
* There are steps for applying object counter on images and videos

**Features**
* Count all objetcs by classes and works perfetcly on every image or on a video
* Code can run on Both (CPU & GPU)
* Video/WebCam/External Camera/IP Stream Supported

## It is super easy to run
* **We are going to copy offical yolov7 github page and just add "detect_and_count.py" file. That is all**
* **When you use Google Colab for codes, it will be way easier than working on the local computer**

## Steps to run Code
* clone the repository:
* ```git clone https://github.com/WongKinYiu/yolov7 ```
* ```%cd yolov7```
* install yolov7 model
* ``` !wget "https://github.com/WongKinYiu/yolov7/releases/download/v0.1/yolov7.pt" ```

### Upgrade pip with mentioned command below.
``` pip install --upgrade pip ```

### Install requirements with mentioned command below.
 ``` pip install -r requirements.txt ```

### Using counter
 ``` !python detect_and_count.py --weights /content/yolov7/yolov7.pt --conf 0.1 --source /content/yolov7/inference/images ```
 
### Results!

![ffdsfdfd](https://user-images.githubusercontent.com/77502485/187065933-0fe4b372-9c40-47ce-bee8-cae6af97605b.jpg)
![indir](https://user-images.githubusercontent.com/77502485/187065517-1ecff689-534f-4aa5-a1e0-06a03ccd8ec9.jpg)


### Stock market detection video:



https://user-images.githubusercontent.com/77502485/191525236-86268939-823f-4852-9c7d-cf7d96a9da78.mp4


# Saving the images of bounding boxes
![carvf](https://user-images.githubusercontent.com/77502485/192260050-1431410d-48fa-4654-92e5-65178d116a84.png)


### References
* https://github.com/WongKinYiu/yolov7

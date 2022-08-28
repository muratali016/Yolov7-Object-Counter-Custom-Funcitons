## *Please read first "README" before browsing the code
# Yolov7-Object-Counter
Object Counting with the newest yolov7

Features
* Count all objetcs by classes and works perfetcly on every image or on a video
* Code can run on Both (CPU & GPU)
* Video/WebCam/External Camera/IP Stream Supported

## It is super easy to run
* We are going to copy offical yolov7 github page and just add "detect_and_count.py" file. That is all 

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

### Inference on a video:
(https://www.youtube.com/watch?v=buekkvf1dr8)
 

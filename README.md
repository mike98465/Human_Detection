# Human_Detection
Pretrained YOLO  deep learning model to detect objects

 ## Dependencies (libraries)
  * openCV
  * numpy

 ## Environment
  * Windows 10
  * Anaconda 3
  * Python 3.6
  * GPU accelerating : cuda 10.1 + cudnn v7.5.1
 
 ## My camera
  * Logitech HD Pro Webcam C920
  
 ## Instructions
 1. Type in your command line: 
 
        git clone https://github.com/mike98465/Human_Detection.git
        cd Human_Detection/
    
 2. Download the weight files on google drive and unzip:
    
    https://drive.google.com/open?id=1M5_ix4jqJhjpXe_79NkGwUS1oM4GIlOA
    
 3. Run
 
        python yolo_webcam_ver.py --config chosen_cfg --weights chosen_weights --classes yolov3.txt
 
 ## Result
 

# Multiview-drone-video-analysis-for-improved-surveillance.
This project focuses on developing an algorithm which performs object detection and tracking in real-time on around 80 different classes of object using OpenCV and YOLOv3.

<h2>About The Project</h2>

This project focuses on developing an algorithm which can enhance the present security and surveillance systems by performing tasks like object detection and object tracking on the set of inputs given, taken mainly through a drone. Various methods were explored while deciding which combination of models for object detection and object tracking gives us the best desirable result. The object detection task is performed using the YOLOv3 model which gives us the respective class along with the confidence score of the object present in the video as the output. The task of object tracking is performed using the concept of centroid-based tracking algorithm, which can do the tracking of multiple objects present in the input video belonging to different classes by providing the coordinates of the moving object and a bounding box with a unique id assigned to it. All the tasks are performed in real-time along with an appreaciable AP(average precision) and FPS(frames per second).

<h2>Environment Set-up</h2>

  - Install [python](https://www.python.org/downloads/) 
  - The python libraries required to execute the code are enlisted below, run the following commands(for python 3) in command prompt(for Windows) to download the respective libraries(use pip instead of pip3 for python 2).
       - Numpy 
         
         ```
         pip3 install numpy
         ```
       - OpenCV
         
         ```
         pip install opencv-python
         ```
                  
         
       - Tensorflow
         
         ```
         pip install tensorflow
         ```
         
       - Keras
         ```
         pip install keras
         ```
       - Matplotlib
                  
         ```
         pip3 install matplotlib
         ```
      
  - Following files would be required to set-up the required environment for proper working of this project:
      - [yolov3 weights](https://pjreddie.com/media/files/yolov3.weights)
      - yolov3.cfg (file given in the repo)
      - coco.names (file given in the repo)
  
   

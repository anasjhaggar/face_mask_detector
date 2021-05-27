<!-- # face_mask_detector
Face mask Detection: This repository include my project details and source files.  

Using YOLOv3, Darknet, OpenCV, CUDA, NumPy, Python, Google Colab, Pycharm


COVID-19 pandemic has rapidly affected our day-to-day life-disrupting world trade and movements. Wearing a protective face mask has become a new normal. Soon, many public service providers will ask the customers to wear masks correctly to avail of their services. Therefore, face mask detection has become a crucial task to help global society. 
Here proposed a solution to the problem of using some basic Machine Learning packages like YOLO, Darknet, OpenCV, and NumPy. The proposed method detects the face from the image correctly and then identifies if it has a mask on it or not. It can also detect a face along with a mask in motion. 
Luckily, there is a publicly available dataset in Kaggle named Face Mask Detection. The dataset contains 853 images and their corresponding annotation files, indicating whether a person is wearing a mask correctly, incorrectly, or not wearing it.
YOLOv3 (You Only Look Once, Version 3) is a real-time object detection algorithm that identifies specific objects in videos, live feeds, or images. Versions 1-3 of YOLO were created by Joseph Redmon and Ali Farhadi. The first version of YOLO was created in 2016, and version 3, which is discussed extensively in this article, was made two years later in 2018.
YOLOv3 is extremely fast and accurate. In mAP measured at .5, IOU YOLOv3 is on par with Focal Loss but about 4x faster. Moreover, you can easily tradeoff between speed and accuracy simply by changing the size of the model, no retraining is required!
YOLOv3 has several advantages over classifier-based systems. It looks at the whole image at test time so its predictions are informed by the global context in the image. It also makes predictions with a single network evaluation unlike systems like R-CNN which require thousands for a single image. This makes it extremely fast, more than 1000x faster than R-CNN and 100x faster than Fast R-CNN.
I trained a model YOLOv3 using darknet on this dataset on Google Colab. After testing that model. I deployed it in Python using OpenCV. Now it can detector if people are wearing a Covid-19 face mask or not, from a video stream, and generate an Alert. 
We already have automatic electric doors and CCTV footage cameras working at the entrance of offices, airports, and other public places. There it can be deployed with their security system.


Anas Abdullah
Lahore, Punjab, Pakistan
anasjhaggar@gmail.com 
https://www.linkedin.com/in/anasjhaggar/ -->

Face Mask Detector

Using YOLOv3, Darknet, OpenCV, CUDA, NumPy, Python, Google Colab, Pycharm

Anas Abdullah -  anasjhaggar@gmail.com 

https://www.linkedin.com/in/anasjhaggar/


The global COVID-19 Pandemic has completely changed our day-to-day lives. It has disrupted World Health and Economy. Wearing a face mask has become a new normal. Public workplaces to private gatherings all have made it mandatory to wear a mask, but just hanging it around ears won't help. We need to wear it correctly to ensure safety. What if we install a system to detect either everyone around, is wearing masks properly or not? 

Here is a way to achieve it. I used some basic Machine Learning packages like YOLO, Darknet, OpenCV, and NumPy. This proposed method detects the face from the image correctly and then identifies if it has a mask on it or not. It can also detect a walking person's mask. 

Luckily, there is a publicly available dataset in Kaggle named Face Mask Detection. The dataset contains 853 images and their corresponding annotation files, indicating whether a person is wearing a mask correctly, incorrectly, or not wearing it. 

YOLOv3 (You Only Look Once, Version 3) is a real-time object detection algorithm that identifies specific objects in videos, live feeds, or images. Versions 1-3 of YOLO were created by Joseph Redmon and Ali Farhadi. The first version of YOLO was created in 2016, and version 3, which is discussed primarily in this article, was made two years later in 2018.

YOLOv3 is extremely fast and accurate. In mAP measured at .5, IOU YOLOv3 is on par with Focal Loss but about 4x faster. Moreover, you can easily tradeoff between speed and accuracy simply by changing the size of the model, no retraining is required!
YOLOv3 has several advantages over classifier-based systems. It detects the whole image at test time, its predictions are informed by the global context in the image. It also makes predictions with a single network evaluation unlike systems like R-CNN which require thousands for a single image. This makes it extremely fast, more than 1000x faster than R-CNN and 100x faster than Fast R-CNN.

I trained a model YOLOv3 using darknet on this dataset on Google Colab. After testing that model. I deployed it in Python using OpenCV. Now it can detector if people are wearing a Covid-19 face mask or not, from a video stream, and generate an Alert. 

We have pre-installed automatic doors system and CCTVs at the entrance of Shopping malls, Offices, Airports, and other public places. They can be deployed with this detection system. This system gets input video stream and processes its runtime to detect a walking-in person either has a proper mask on or not, either wears correctly, like his nose and mouth is fully covered? The system generates an alert immediately based on the detection.  We can take preventive actions based on respective alerts as an alarm rings or red-light beeps on the controlling door.

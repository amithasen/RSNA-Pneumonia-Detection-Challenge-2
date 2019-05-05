# RSNA-Pneumonia-Detection-Challenge
RSNA Pneumonia Detection Challenge
(Final Project for Data Mining)

Submitted to:
Pantelis Monogioudis

(Head of the Applied Machine Learning Department @ Bell Labs.
Adjunct Prof. @NJIT)


Submitted by:

•	Atul Avijeet

•	Saurav Harjai

•	Subhasree Kurusamy


Overview:
To build an algorithm to detect a visual signal for pneumonia in medical images. Specifically, your algorithm needs to automatically locate lung opacities on chest radiographs.

 

What is Pneumonia?
Pneumonia is an infection that inflames the air sacs in one or both lungs. The air sacs may fill with fluid or pus (purulent material), causing cough with phlegm or pus, fever, chills, and difficulty breathing. A variety of organisms, including bacteria, viruses and fungi, can cause pneumonia.

Pneumonia can range in seriousness from mild to life-threatening. It is most serious for infants and young children, people older than age 65, and people with health problems or weakened immune systems.

What are symptoms of Pneumonia?

•	Chest pain when you breathe or cough

•	Confusion or changes in mental awareness (in adults age 65 and older)

•	Cough, which may produce phlegm

•	Fatigue

•	Fever, sweating and shaking chills

•	Lower than normal body temperature (in adults older than age 65 and people with weak immune systems)

•	Nausea, vomiting or diarrhea

•	Shortness of breath


Mask R-CNN
It is a conceptually simple, flexible, and general framework for object instance segmentation. The approach efficiently detects objects in an image while simultaneously generating a high-quality segmentation mask for each instance. The method, called Mask R-CNN, extends Faster R-CNN by adding a branch for predicting an object mask in parallel with the existing branch for bounding box recognition. Mask R-CNN is simple to train and adds only a small overhead to Faster R-CNN, running at 5 fps. Moreover, Mask R-CNN is easy to generalize to other tasks, e.g., allowing us to estimate human poses in the same framework. This show top results in all three tracks of the COCO suite of challenges, including instance segmentation, bounding-box object detection, and person keypoint detection. Without bells and whistles, Mask R-CNN outperforms all existing, single-model entries on every task, including the COCO 2016 challenge winners. 
This is an implementation of Mask R-CNN on Python 3, Keras, and TensorFlow. The model generates bounding boxes and segmentation masks for each instance of an object in the image. It's based on Feature Pyramid Network (FPN) and a ResNet101 backbone.

Acknowledgements:
•	Thank you to my Prof. Pantelis Monogioudis, for guiding our project.

•	Thank you to the National Institutes of Health Clinical Center for publicly providing the Chest X-Ray dataset.

•	To original source files and documents.

•	To Google Colab and Stack Overflow.

•	Thanks to Vencent Chen for grading this project.



References
•	Kernel: Mask R-CNN for Object Detection and Segmentation on Github- https://github.com/matterport/Mask_RCNN

•	Kernel: START HERE: Beginner Intro to Lung Opacity S1
https://www.kaggle.com/giuliasavorgnan/start-here-beginner-intro-to-lung-opacity-s1

•	Kernel: RSNA Pneumonia Detection EDA-
            https://www.kaggle.com/gpreda/rsna-pneumonia-detection-eda

•	RPN mask r-cnn regions exploration on RSNA data- https://www.kaggle.com/kretes/rpn-mask-r-cnn-regions-exploration-on- rsna-data

•	Google Colab tutorials
          



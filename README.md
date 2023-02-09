# Face-Detection-and-Recognition-with-Python
This repository contains codes related to face detection using Haarscared, HOG, MMDO, SSD, OpenCV. Recogniton using Eigenfaces, Fisherfaces, LBPH, Deep Learning(dlib, face recogniton).
Projetcs video webcam.

![!Yolo Object Detection](https://github.com/gslmota/Face-Detection-and-Recognition-with-Python/blob/main/images/cp.png)
*Original image: [Open Imagens Dataset](https://storage.googleapis.com/openimages/web/index.html)*

# Contents
``` shell
.
├── code_python
│   ├── deploy.prototxt.txt
│   ├── eigen_classifier.yml
│   ├── encoding_faces.py
│   ├── face_capture_webcam.py
│   ├── face_detection_webcam.py
│   ├── face_encodings_custom.pickle
│   ├── face_names.pickle
│   ├── fisher_classifier.yml
│   ├── haarcascade_frontalface_default.xml
│   ├── helper_functions.py
│   ├── lbph_classifier.yml
│   ├── recognition_deeplearning_webcam.py
│   ├── recognition_webcam.py
│   ├── res10_300x300_ssd_iter_140000.caffemodel
│   └── train_recognizers.py
├── images
│   ...
├── jupyter_notebooks
│   ├── Face_Recognition_in_Videos_.ipynb
│   ├── Reconhecimento_Facial_com_Deep_Learning.ipynb
│   └── Reconhecimento_Facial_Métodos_tradicionais.ipynb
├── LICENSE
└── README.md
```
The **Python_codes** folder contains the python codes used in projects. Folder **Notebooks_Colab** contains the notebooks developed with the stacks.

# Requirements

 * Check the **requirements.txt** file.


# Use

```shell
git clone https://github.com/gslmota/Face-Detection-and-Recognition-with-Python.git
cd Face-Detection-and-Recognition-with-Python
pip install -r requirements.txt
```


# Results

 * **Face Detection and Landmarks**:

![!Yolo Object Detection](https://github.com/gslmota/Object_Detection_using_Yolo_Darknet_OpenCv_Python/blob/main/img/resultado_cachorro.jpg)
*Original image: [Open Imagens Dataset](https://storage.googleapis.com/openimages/web/index.html)*

 
 * **Video Detection**:
 
 ![!YOLO Darknet  detection video](https://github.com/gslmota/Object_Detection_using_Yolo_Darknet_OpenCv_Python/blob/main/img/roadusa3_1.gif)


# References:
* Open Imagens Dataset: [Open Imagens Dataset](https://storage.googleapis.com/openimages/web/index.html)
* YOLOv4 model: [YOLOv4 Repository](https://github.com/AlexeyAB/darknet)
* IA Expert Academy: [Detecção de Objetos com YOLO, Darknet, OpenCV e Python](https://iaexpert.academy/cursos-online-assinatura/deteccao-de-objetos-com-yolo-darknet-opencv-e-python/)


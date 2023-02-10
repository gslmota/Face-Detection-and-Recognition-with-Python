# Face-Detection-and-Recognition-with-Python
This repository contains codes related to face detection using Haarscared, HOG, MMDO, SSD, OpenCV. Recogniton using Eigenfaces, Fisherfaces, LBPH, Deep Learning(dlib, face recogniton).
Projetcs video webcam.

![!Yolo Object Detection](https://github.com/gslmota/Face-Detection-and-Recognition-with-Python/blob/main/images/cp.png)

*Original image: [Yale Faces](https://sthttp://cvc.cs.yale.edu/cvc/projects/yalefaces/yalefaces.html)*

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
**Face Detection and Landmarks** using Dlib and deep learning.
![!Face Detection and Landmarks](https://github.com/gslmota/Face-Detection-and-Recognition-with-Python/blob/main/images/d1.png)

*Original image: [Yale Faces](https://sthttp://cvc.cs.yale.edu/cvc/projects/yalefaces/yalefaces.html)*

 
 * **Face Recognition**:
 **Face Recognition** using Dlib and deep learning.
 ![!Face Recognition](https://github.com/gslmota/Face-Detection-and-Recognition-with-Python/blob/main/images/d2.png)

 *Original image: [Yale Faces](https://sthttp://cvc.cs.yale.edu/cvc/projects/yalefaces/yalefaces.html)*

 * **Celebrity Recognition**:
 **Celebrity Recognition** using lib face_recognition.
 ![!Celebrity Recognition](https://github.com/gslmota/Face-Detection-and-Recognition-with-Python/blob/main/images/ae1.png)

 ![!Celebrity Recognition](https://github.com/gslmota/Face-Detection-and-Recognition-with-Python/blob/main/images/ae2.png)

 ![!Celebrity Recognition](https://github.com/gslmota/Face-Detection-and-Recognition-with-Python/blob/main/images/wol1.png)

 ![!Celebrity Recognition](https://github.com/gslmota/Face-Detection-and-Recognition-with-Python/blob/main/images/wol2.png)


 * **Video Celebrity Recognition**:
 **Video Celebrity Recognition** using lib face_recognition.
 ![!Video Celebrity Recognition](https://github.com/gslmota/Face-Detection-and-Recognition-with-Python/blob/main/images/vid.gif))

* **Drawing of facial elements**:
 **Drawing of facial elements** using lib face_recognition.
 ![!Drawing of facial elements](https://github.com/gslmota/Face-Detection-and-Recognition-with-Python/blob/main/images/fl.png))


# References:
* Yale Faces: [Yale Faces](https://sthttp://cvc.cs.yale.edu/cvc/projects/yalefaces/yalefaces.html)

* IA Expert Academy: [Detecção de Objetos com YOLO, Darknet, OpenCV e Python](https://iaexpert.academy/cursos-online-assinatura/deteccao-de-objetos-com-yolo-darknet-opencv-e-python/)


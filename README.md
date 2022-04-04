Due to ongoing Corona pandemic, wearing mask has become an integral part of our lives. Nowadays it is important to wear a face mask to ensure the safety of ourself and others.I have created a simple object detection model that can detect whether you are wearing a mask or not. I have utilized the object detection API and tensorflow framework and used a pretrained model RetinaNet50 from "Model Zoo". I have used face mask detection datasets from "kaggle". The model has achieved 90% accuracy with testing data.

# With_Mask
![with_mask](https://user-images.githubusercontent.com/82416394/161498942-32daf959-facb-4500-92a9-1fe12bdaccd8.JPG)

# Without_Mask
![without_mask](https://user-images.githubusercontent.com/82416394/161498965-8c381e9c-7e4b-41a0-b059-c3863b30e1e6.JPG)

Link :  https://blog.tensorflow.org/2020/07/tensorflow-2-meets-object-detection-api.html

object detection repo: https://github.com/tensorflow/models/tree/master/research/object_detection

Tensorflow Models Repo : https://github.com/tensorflow/models

Tensorflow Model Selection : https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/tf2_detection_zoo.md



# Steps:

1 . Installation of necessary libraries

2. Preparing dataset for Custom Training

3. Using a Pretrained Model

4. Creating a Labelmap.pbtxt

5. Creating xml to csv

6. Creating tensorflow records files from csv

7. Getting the config file and do the necessary changes

8. Start the training

9. Model Evaluation

10. Exporting the graph

11. Doing prediction on trained model
12. Using webcam for Prediction

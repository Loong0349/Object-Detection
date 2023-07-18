# Object-Detection

This is a final-year project titled "dangerous object detection using machine learning". 

The proposed methodology involves training a machine learning model using the ExDark dataset and the YOLOv5 object detection framework. Prior to training, the dataset undergoes a transformation process using the AGLLNet image enhancement technique to enhance image quality and visibility. The transformed dataset is then preprocessed and converted into the YOLOv5 PyTorch format using Roboflow before being trained with YOLOv5.

References and links:

Exdark dataset : https://github.com/cs-chan/Exclusively-Dark-Image-Dataset

Exdark anno to Yolo : https://github.com/aweihao/ExDark2Yolo

AGLLNet Image enhancement : https://github.com/yu-li/AGLLNet

Roboflow dataset : https://app.roboflow.com/sunway-university/dangerous-road-objects

Yolov5 : https://colab.research.google.com/drive/1KVPLN4MYiM1GA6CgghhKvDvguzzPCJlX?usp=sharing


Results and discussion

![image](https://github.com/Loong0349/Object-Detection/assets/70373779/686f9083-dfed-46f9-bcf0-e1a76bfc4615)
![image](https://github.com/Loong0349/Object-Detection/assets/70373779/ffdf0049-257b-4ccb-b2d2-77e8a19153e2)

The results of the study demonstrate the model's decent performance in predicting dangerous objects, with precision, recall, and mean average precision scores varying for different classes such as bicycles, buses, cars, motorbikes, and people. However, the model exhibits limitations in distinguishing between similar or overlapped objects, suggesting the need for further improvements such as data augmentation and architectural refinements.

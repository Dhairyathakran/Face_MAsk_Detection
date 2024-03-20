# Face_MAsk_Detection
Mask_detection model

We annotate our data Using Roboflow

Then export the file into googel colab using this

Change it via your workspacename on Roboflow and Change the name of folder do you want

!pip install roboflow

from roboflow import Roboflow
rf = Roboflow(api_key="oaSwA6w5F7VRpQb28Mqs")
project = rf.workspace("hyssam-baccouche").project("face-mask-detection-djzcc")
dataset = project.version(1).download("yolov7")


# we can chage the name of data folder also change the training model name we select the model which we want .

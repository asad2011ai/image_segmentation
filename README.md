# image_segmentation Prediction using pretrianed weight of Mask RCNN
Create folder : Dataset

In Dataset folder create 2 folders : train and val Put training images in train folder and validation images in Val folder.

Download mrcnn folder from this repository: https://github.com/matterport/Mask_RCNN

Download coco weights : https://github.com/matterport/Mask_RCNN/releases/download/v2.0/mask_rcnn_coco.h5

# trained model for sidewalk segmentation on Custom Dataset

# orignial image

![sidewalk40](https://user-images.githubusercontent.com/88252108/176420990-6c2f52c7-bd24-43a1-9083-f90bfed02130.jpeg)

# predicted image by a trained custom sidewalk model

![sidewalk image segmetation](https://user-images.githubusercontent.com/88252108/176421095-03ba9f8b-b543-4fdb-8608-e7e43f6a8dbe.png)

# comparison Graph for training and validation loss 
from these graph we can see that our best training model is exist between 270 to 280 epochs

# training loss graph
![training_loss](https://user-images.githubusercontent.com/88252108/176432770-554eb706-d09d-4cc7-8a04-715e545d2ddf.jpg)

# validation loss
![validation_loss](https://user-images.githubusercontent.com/88252108/176432972-325742fd-9508-4f47-8843-5216837a1726.jpg)
# Epoch 374 is best as compared to above graphs
![Capture](https://user-images.githubusercontent.com/88252108/176432309-94c89e7a-35de-4a82-902a-a80762845398.PNG)


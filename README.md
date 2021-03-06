# dog-detector

The **DOG-DETECTION.pdf** explains in detail the procedure followed to train YOLO darknet on a custom dogs dataset.
<br>
<br>
The rest of the readme explains the function of each of the uploaded files:
> - **test_sample_images** folder contains the test images 
> - **bbox_to_yolo_format.py** file converts the annotations to the format desired by yolo
> - **process.py** file creates the files train_dogs.txt and test_dogs.txt for training and validation data
> - **dog.names** this stores names of all classes to be trained in the model. In this case it contains single class - 'dog'
> - **dogs.data** this stores the path to the train_dogs.txt, test_dogs.txt, dog.names and backup folder (where the weights get stored)
> - **dogs.cfg** this is the yolo architecture configuration file for this dataset.

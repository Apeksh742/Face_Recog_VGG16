# Face_Recog_VGG16 model

Pre-requisites: cv2 module, keras, numpy and pillow library.

Step 1: Created Dataset of images using cv2 module from collecting samples code. Adjust location according to your comfort
and i used the same code for Training and Validation dataset by changing location and changing number of count images.

For proper face detection i have used harcascade classifier.

NOTE: Dataset must be in following order : Dataset -> Training , Testing -> Classes of Dataset in each folder with photos

Step 2: Trained my model by using VGG16 pre-trained model in which i have freezed all layers except last FC layers
and created new FC layers using addTopModel function and provided my Dataset

Step 3: Then predict result from a photo .


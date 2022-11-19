# Face detection with YOLOv5

The provided notebook uses the [WIDER FACE](http://shuoyang1213.me/WIDERFACE/) dataset to train and yolov5s model to detect faces.
The notebook was created in Google Colab and can be accessed [here](https://colab.research.google.com/drive/1kQkioaIgxtNrFtT349VLqNhW-wiQxwM1?usp=sharing).
The trained model can be downloaded from Google Drive [here](https://drive.google.com/file/d/18VJoBepSDGoTgS9pDmwwUBOLXpJkH6h1/view?usp=sharing).
If using the trained model, place it in the 'yolov5' directory, and detect will work as is.
If you train your own model, remember to change the --weights argument in the detecdt section.

The notebook will also run locally with slight modifications: remove any functions / imports that use google drive, delete the first code block in the Detect section, and set --source 0 in the following code block.

The notebook includes a detection section that uses the webcam to predict the presence of faces.

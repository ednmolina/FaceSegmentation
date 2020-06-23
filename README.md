# FaceSegmentation
## Facial Segmentation Project using Detectron2

The motivation for this project was to create a method to automatically detect faces from photos in Black Lives Matter protest photos to conceal the identities of those participating.

# Requirements
* Python 3.6.9
* Detectron2
* OpenCV
* numpy
* matplotlib

# Data
The training and testing data can be found in the `train` and `test` folders. The model will also need the `test.json` and `train.json`files for information about the respective datasets.

# Future Improvements
Future Improvements for this project would be:
  * Discriminating civilian and officer faces to conceal on the faces of civilians
  * Fine turning the model to optimize hyper parameters

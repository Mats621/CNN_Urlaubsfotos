# CNN_Urlaubsfotos

## Task
- Implement simple Convolutional Neural Network for image classification on an own dataset
- Chosen dataset is containing 2979 private images (prefiltered for good labels)
- CNN should classify pictures into `person` and `scene` classes
--- 
## Approach
- Using pytorch for implementation of CNN
- Changing Hyperparameters manually first to get a feeling for the values and their impact
- Save models
- Save graph of training and validation losses
- Save output of training loop into txt file
---
## To be done
- Automatic Hyperparameter optimization (mabye with RayTune)
- Try TransferLearning to solve the problem, using ResNet
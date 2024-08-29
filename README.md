# MRI-brain
Project Title: Minimised CNN for Multi-Class Brain Tumour Detection in MRI Scans

I have uploaded 13 files in total.
PDM file contains Project and Data Management Plan of my project.

'initial-code' file contains the code that was developed initially during this project.

As per the project description, I have developed codes in files Model 11CNN, Model 12CNN, Model 13CNN, Model 14CNN by experimenting the code with different parameters to check how many number of layers(Model 11 cNN) is the best, then using that and changing kernel sizes (Model 12CNN) to know which one gives best result.
In Model 13 CNN I have used best number of layers and kernel size, to understand which optimizer gives best result.
Lastly applied the best number of layers, kernel size, optimizer from previous models (Model 11CNN, Model 12CNN, Model 13CNN) to understand which activation function(Model 14CNN) gives good result to better understand how things are working before going with pretrained models.

Taking into consideration regarding further tuning and further code development 5 distinct DL models are employed for the identification of Brain Tumours in the minimised CNN are in the following: 

•	Model 1 CNN - Number of Layers (captures no tumor, tumor region)
•	Model 2 CNN - Kernel Sizes
•	Model 3 CNN - Optimizers
•	Model 4 CNN- Activation Functions
•	Model 5 CNN- Batch Sizes

Pretrained Models used and respective code files (by applying the best number of layers, kernel size, optimizer, activation function and batch size from above experimentation) :
Pretrained Model 1 - VGG16
Pretrained Model 2 - ResNet50
Pretrained Model 3 - GoogleNet

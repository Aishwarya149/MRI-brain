# MRI-brain
Project Title: Minimised CNN for Multi-Class Brain Tumour Detection in MRI Scans

Dataset Selection:
MRI Dataset (7,023 brain images) utilized in this research is sourced from Kaggle (Nickparvar, 2023) https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset?select=Training classified into 5 distinct types: These are pituitary, glioma, no tumor, astrocytoma, and meningioma. Images used in this research were obtained from Figshare, SARTAJ, and Br35H datasets and are in JPG or PNG format. In particular, the dataset comprises 1,321 images of glioma, 1,339 of meningioma, 1,595 of no tumors, and 1,457 of pituitary, while the rest is labelled as astrocytomas. The dataset contains images of patients with no direct references to patients’ identities, which makes it GDPR-compliant

I have uploaded 14 files in total(excluding  README file and dataset).

PDM file contains Project and Data Management Plan of my project to give an overview about the research question and objective of this project.

'initial-code' file contains the code that was developed initially during this project.

As per the project description, I have developed codes in files Model 11CNN, Model 12CNN, Model 13CNN, Model 14CNN by experimenting the code with different parameters to check how many number of layers(Model 11 cNN) is the best, then using that and changing kernel sizes (Model 12CNN) to know which one gives best result.
In Model 13 CNN I have used best number of layers and kernel size, to understand which optimizer gives best result.
Lastly applied the best number of layers, kernel size, optimizer from previous models (Model 11CNN, Model 12CNN, Model 13CNN) to understand which activation function(Model 14CNN) gives good result to better understand how things are working before going with pretrained models.

Taking into consideration regarding further tuning and further code development, 5 distinct DL models are employed for the identification of Brain Tumours in the minimised CNN are in the following: 

•	Model 1 CNN - Number of Layers (captures no tumor, tumor region)
•	Model 2 CNN - Kernel Sizes
•	Model 3 CNN - Optimizers
•	Model 4 CNN- Activation Functions
•	Model 5 CNN- Batch Sizes

Pretrained Models used and respective code files (by applying the best number of layers, kernel size, optimizer, activation function and batch size from above experimentation) to know which pretrained model gives best results:
Pretrained Model 1 - VGG16
Pretrained Model 2 - ResNet50
Pretrained Model 3 - GoogleNet

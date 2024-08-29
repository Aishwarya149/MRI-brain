# MRI-brain
Minimised CNN for Multi-Class Brain Tumour Detection in MRI Scans
Research Question:
1.	Can a minimised CNN architecture offer a fast, accurate, and reliable solution for multi-class brain tumour classification in MRI scans?
2.	Which CNN architecture configuration (number of layers, kernel size, etc.) achieves the best balance between accuracy and training efficiency?

Research Objectives:
•	To conduct a detailed literature review of existing literature on brain tumour classification using various deep learning techniques and analyse its strengths and limitations.
•	To collect the brain tumour MRI dataset from the Kaggle website and pre-process the data by performing necessary steps such as resizing, normalization, and splitting the data into training, validation, and testing sets.
•	To implement and train the CNN model for multi-class brain tumour classification and experiment with different configurations, including the number of layers, kernel sizes, batch sizes, optimizers, and activation functions.
•	To evaluate the performance of each model configuration for multi-class classification using appropriate metrics, such as accuracy, precision, recall, and F1-score and identify the best-performing model configuration that achieves the highest accuracy for multi-class classification while minimizing training time and model complexity.

Summary of Project and Background
Brain tumours are very dangerous if they are not detected or treated early. Magnetic Resonance Imaging (MRI) is a non-invasive technique that has been used in imaging the brain in detail (Senan et al, 2022). Hence it is very essential in the detection and analysis of brain tumours. Nevertheless, the visual analysis of MRI scans by radiologists is a rather tedious, subjective, and error-prone process, especially when dealing with numerous cases and heterogeneous tumour manifestation (Gaur et al, 2022). New developments in the field of deep learning, especially CNNs have provided high performance in medical image analysis problems such as the identification of brain tumours. CNNs perform very well in learning and identifying features from image data and therefore apply well in image categorization, division, and identification (Chattopadhyay and Maitra, 2022). This research work aims to design a reduced CNN model for multi-class brain tumour identification from MRI images. Therefore, to achieve the optimal CNN model that can balance both the classification accuracy and the training time, the following parameters will be tested out; the number of layers, the kernel size, the batch size, the optimizer, and the activation function etc. The reduced CNN architecture may provide a quicker and more effective way for brain tumour classification, which is more suitable for clinical use.

References:
Senan, E.M., Jadhav, M.E., Rassem, T.H., Aljaloud, A.S., Mohammed, B.A. and Al-Mekhlafi, Z.G., 2022. Early diagnosis of brain tumour mri images using hybrid techniques between deep and machine learning. Computational and Mathematical Methods in Medicine, 2022(1), p.8330833.
Gaur, L., Bhandari, M., Razdan, T., Mallik, S. and Zhao, Z., 2022. Explanation-driven deep learning model for prediction of brain tumour status using MRI image data. Frontiers in genetics, 13, p.822666.
Chattopadhyay, A. and Maitra, M., 2022. MRI-based brain tumour image detection using CNN based deep learning method. Neuroscience informatics, 2(4), p.100060.
 
 
Task List and Project Timeline

Tasks	Description	Start Date	End Date
Choosing a Project	Choosing the project domain and title	14-05-2024	14-05-2024
Literature Review	Conduct a comprehensive review of existing literature on neural network architecture, especially CNN architectures in fake news detection	14-05-2024	26-05-2024
Data Acquisition	Obtain and pre-process the required dataset from the specified sources.	27-05-2024	04-06-2024
Data Analysis	Analyze the datasets using vectorization techniques and visualizations.	05-06-2024	15-06-2024
PDM Plan Submission	Prepare and submit the Project and Data Management (PDM) plan.	10-06-2024	14-06-2024
Initial Model Development	Develop and train the chosen a CNN model with different   configurations.	04-06-2024	03-07-2024
Comparative Analysis	Compare the performance (accuracy and speed) of CNN with different configurations	01-07-2024	10-07-2024
Data Ethics Quiz	Prepare and take the ethics quiz.	02-07-2024	02-07-2024
Model Development and Evaluation	Build and evaluate the CNN models using metrics	10-07-2024	14-08-2024
Preparing Final Project Report 	Document the findings, and prepare the final report.	10-08-2024	30-08-2024
FPR Submission	Submit the FPR Report	29-08-2024	30-08-2024
Viva Preparation	Prepare and submit the final project report.	02-09-2024	20-09-2024
Viva	Conduct the viva presentation	10-09-2024	16-09-2024

  
Data Management Plan

Data Collection
The project utilises a dataset Brain Tumor MRI Dataset which is collected from https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset?select=Training

Overview of the Dataset
The dataset consisting of 7023 brain MRI images is classified into four categories: The types of tumours include astrocytoma, glioma, meningioma, no tumour and pituitary. This dataset is collected from figshare, SARTAJ dataset, and Br35H dataset. The format of the files is probably JPG or PNG image files. We have a total of 7023 images in the dataset, where 1321 images are related to glioma, 1339 to meningioma, 1595 to no tumour, and 1457 to the pituitary. 

Summary of Data
The sum of the size of the dataset is about 156 MB, and the expected size of the data and code will be 12 to 25 MB.

Document Control
To manage and share the code of the project, the code will be uploaded into a GitHub repository. The dataset and the code will be accessed using the link: https://github.com/Aishwarya149/MRI-brain/tree/main

Metadata
A ReadMe file will be included in the GitHub repository of the project that contains an overview of the project, how to set up and run it, information about datasets notes on dependencies, and contact details.

Security and Storage
Getting backup will be done daily whenever there is active development and weekly during maintenance with data backed up in GitHub. Data will be exchanged with the staff as well as markers using the GitHub repository after it has been made secure.

Ethical Requirements
The project is compliant with ethical principles; the dataset contains images of patients with no direct references to patients’ identities, which makes it GDPR-compliant. In addition, the data used in this research has been collected from publicly available data sources that observe the right conduct in data collection. Hence, this dataset does not violate the UH guidelines.


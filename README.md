# ROP-Detection-Using-Deep-Learning
Link to Dataset: https://www.kaggle.com/datasets/zohaibaslam03/augmented-dataset <br/> <br/>
This repository contains detection and classification of Retinopathy of Prematurity using deep learning. This was a project for our university course "Introduction to Deep Learning". Retinopathy of Prematurity (ROP) is a vision-threatening eye disorder that primarily affects premature infants. It occurs when abnormal blood vessels grow and spread in the retina, potentially leading to retinal detachment and blindness if untreated. This project utilizes several models, such as CNN, ResNet, EfficientNet and VGG19 to detect and classify ROP based on retinal images provided, with each model achieving a different accuracy score. The dataset contains retinal images of infants, along with diagnosis codes (DG0, DG1 etc), which tells the severity of ROP. Lower diagnosis code corresponds to less severe ROP, while higher diagnosis codes correspond to increasing severity of ROP. Some changes were also made to the original dataset, such as organzing the images into subfolders based on their diagnosis codes and using augmentation. All the models performed well, achieving the following accuracies. <br/> <br/>
CNN: Test Accuracy 98.48%, Test Loss: 0.06 <br/>
ResNet: Test Accuracy: 95.35%, Test Loss: 0.14 <br/>
EfficientNet: Test Accuracy: 96.07%, Test Loss: 0.13 <br/>
Inception: Test Accuracy: 91.83%, Test Loss: 0.25 <br/>
VGG19: Test Accuracy: 88.86%, Test Loss: 0.32

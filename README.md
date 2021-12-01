# Pathology Detection in X-rays using machine learning
This project aims to detect pathologies from chest X-Rays using machine learning. 
The data was taken from ChestX-Ray14 dataset. Here, I focus on a pathology called Cardiomegaly which is the enlargement of heart. 
Pre-processing involved steps like handling patient overlap, cleaning and splitting the data. Transfer learning was used to train the model and experiments were conducted using various versions of DenseNet. The best model achieved an AUROC score of 0.911.

Machine learning models cannot be used blindly especially in the field of medicine without providing an explanation for the prediciton given by the model. Grad-CAM was used to provide a visual explanation for the model, an example of which is given below.

![image](https://user-images.githubusercontent.com/66838626/144295897-649a2d73-6aa3-4bb2-ad1e-b3fdcaf67b5a.png)

Future works of this model can include expanding the model to predict multiple pathologies and include additional data.

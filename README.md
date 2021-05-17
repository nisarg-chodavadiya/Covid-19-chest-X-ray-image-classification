# Covid-19-chest-X-ray-image-classification
Image classification of chest X-ray images with four different classes. Classes are Normal, Covid19, Viral Pneumonia and Bacterial Pneumonia using pre-trained Resnet-50 with imagenet weights.
 
# Dataset
Source(Covid19 images): https://github.com/ieee8023/covid-chestxray-dataset 
Source(Pneumonia and Normal images): https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia
 
![Covid chest xray](https://user-images.githubusercontent.com/75474944/118405322-08442c80-b695-11eb-9e08-19f67173a6d0.png)
 
# Preprocessing
## Folder Structure
{0: 'Covid-19', 1: 'Normal', 2: 'Viral Pneumonia', 3: 'Bacterial Pneumonia'}
```
|__ train:
    |______ 0: [.....]
    |______ 1: [.....]
    |______ 2: [.....]
    |______ 3: [.....]
|__ test:
    |______ 0: [.....]
    |______ 1: [.....]
    |______ 2: [.....]
    |______ 3: [.....]
 ```
# Model:
![results](https://user-images.githubusercontent.com/75474944/118405313-fb273d80-b694-11eb-9559-4c57909d92a4.png)


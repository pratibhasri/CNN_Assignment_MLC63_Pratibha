# Project Name
This assignment is to  build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early.

## Table of Contents
1. Import the image dataset 
2. Visualize the data for understanding 
3. Start with a 3 layer model 
4. Split into test and train data
5. Result analysis for accuracy , overfitting or underfitting
6. Add dropout layers to reduce overfitting
7. Data augmentation and modelling 
8. Result analysis 
9. Conclusion 



## General Information
 Melanoma is a type of cancer that can be deadly if not detected early.A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.The dataset consists of 9 types of skin cancer.
 

## Conclusions
With initial 3layer model , training accuracy is ~85 % but validation accuracy is ~60 % only , hence there is a huge difference between training and validation data indicating overfitting.
Hence next model is made using drop out layers , here the  training and validation accuracy have reduced to ~50 % , but overfitting is not observed.
Further to improve model accuracy , we incorporate data augmentation for each case . Post data augmentation and drop out layers , the training accuracy achieved is satisfactory and training and validation accuracy are very closely matching .





## Technologies Used
sklearn 
smstats 
Pandas
Seaborn
Matplotlib
keras
glob
tensorflow

## Acknowledgements
I would to thank The Upgrad Professors for helping me understand the concepts of linear regression.


## Contact
Created by [@PratibhaSri - feel free to contact me!



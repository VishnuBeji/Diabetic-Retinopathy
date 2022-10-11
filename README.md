## Diabetic-Retinopathy

Diabetic retinopathy is the leading cause of blindness in the working-age population of the developed world. It is estimated to affect over 93 million people. Diabetic Retinopathy classification is a challenging problem where we are required to classify the fundus image of the retina into either of the 5 grades of Diabetic Retinopathy. 

This can be massively improved with 
* high-resolution images
* better data sampling
* ensuring there is no leaking between training and validation sets, ```sample(replace = True)``` is real dangerous
* better target variable (age) normalization
* pretrained models
* attention/related techniques to focus on areas.

![alt text](https://github.com/VishnuBeji/Diabetic-Retinopathy/images/Fundusimg.jpg?raw=true)

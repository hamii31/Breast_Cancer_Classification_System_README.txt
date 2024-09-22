# Breast_Cancer_Classification_System_README.txt
### Title

Breast Cancer Classification System

### Description

The BCCS Iidentifies if a breast tumor is malignant or benign with the use of a text classification machine learning model and a more complex image classification deep learning model.

**Text input** is comprised of ten-real world values, that are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. They describe characteristics of the cell nuclei present in the image. The values are:

a) radius (mean of distances from center to points on the perimeter) b) texture (standard deviation of gray-scale values) c) perimeter d) area e) smoothness (local variation in radius lengths) f) compactness (perimeter^2 / area - 1.0) g) concavity (severity of concave portions of the contour) h) concave points (number of concave portions of the contour) i) symmetry j) fractal dimension ("coastline approximation" - 1)

The mean, standard error and "worst" or largest (mean of the three largest values) of these features were computed for each image, resulting in 30 features. For instance, field 3 is Mean Radius, field 13 is Radius SE, field 23 is Worst Radius.

The text input is taken from a Windows Form and sent to the trained model, the answer comes within seconds as a pop-up. 

**Image input** is a picture of a microscopic section of the tumor uploaded by the user directly into an extension of the Windows Form. The image file is sent to the alocated methods and trained model. The answer comes within seconds as a pop-up as well. 

For best results, use both inputs for the same tumor. 

### Showcase of the Image Classification Model

The first picture is of a Benign Breast Tumor, the second is of a Malignant Breast Tumor. Both pictures** did not** partake in the training of the model.

https://github.com/user-attachments/assets/9327b091-5eba-4de9-81f4-6b0fe7bb3430




# Predicting-Lymphoma-using-CNN-in-Keras
### Classifying histopathology slides of Lymphoma as malignant or benign using CNN

Dataset
==========
The original dataset consisted of 4 types of 113 whole mount slide images(2560x1920) of Lymphoma specimens scanned at 20x. From each type of mother image, around 42,750 child patches of size 100 x 100 were extracted (roughly 23,275 negative and 19,475 positive). 

Each type of mother image file name is of the format: **type_patientID_class.tif**

| Example    | Example     | Type         | Type serial |
|------------|-------------|--------------|-------------|
|2_neg.tif|7_pos.tif|MYC IHC|0|
|dab_2_neg.tif|dab_7_pos.tif|DAB(MYC signal)|1|
|dist_2_neg.tif|dist_7_pos.tif|Distance map of positive nuclei|2|
|hem_2_neg.tif|hem_7_pos.tif|Hematoxylin(blue counterstrain)|3|

| Benign(-)  | Malignant(+)|
|------------|-------------|
| MYC IHC |
| <img src="/readme/2_neg.jpg" height="200" width="250" > | <img src="/readme/7_pos.jpg" height="200" width="250" >  |
| DAB(MYC signal) |
| <img src="/readme/dab_2_neg.jpg" height="200" width="250" > | <img src="/readme/dab_7_pos.jpg" height="200" width="250" >  |
| Distance map of positive nuclei  |
| <img src="/readme/dist_2_neg.jpg" height="200" width="250" > | <img src="/readme/dist_7_pos.jpg" height="200" width="250" >  |
| Hematoxylin(blue counterstrain) |
| <img src="/readme/hem_2_neg.jpg" height="200" width="250" > | <img src="/readme/hem_7_pos.jpg" height="200" width="250" >  |

Training
==========
For training, size of trainset is 90x4 and testset is 23x4 out of 113x4 mother images. 113 mother images of a type is shuffled, then randomly 90 images of that type along with other 3 types holding same patientID are selected for trainset(90x4).












Feedback
==========
Please send me your feedback at sandipsahajoy@ualberta.ca

Reference
==========
1. https://www.ncbi.nlm.nih.gov/pubmed/27093450

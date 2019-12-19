# Predicting-DLBCL-using-CNN-in-Keras
```
Classifying histopathology slides of Lymphoma as malignant or benign using CNN
```
Dataset
==========
The original dataset consisted of 113 whole mount slide images of Lymphoma specimens scanned at 20x. From that, 277,524 patches of size 50 x 50 were extracted (198,738 IDC negative and 78,786 IDC positive). Each patch’s file name is of the format: u_xX_yY_classC.png — > example 10253_idx5_x1351_y1101_class0.png . Where u is the patient ID (10253_idx5), X is the x-coordinate of where this patch was cropped from, Y is the y-coordinate of where this patch was cropped from, and C indicates the class where 0 is non-IDC and 1 is IDC.
| Benign(-)  | Malignant(+)|
|------------|-------------|
| DLBCL MYC IHC |
| <img src="/readme/2_neg.jpg" height="200" width="300" > | <img src="/readme/7_pos.jpg" height="200" width="300" >  |
| DAB(MYC signal) |
| <img src="/readme/dab_2_neg.jpg" height="200" width="300" > | <img src="/readme/dab_7_pos.jpg" height="200" width="300" >  |
| Distance map of positive nuclei  |
| <img src="/readme/dist_2_neg.jpg" height="200" width="300" > | <img src="/readme/dist_7_pos.jpg" height="200" width="300" >  |
| Hematoxylin(blue counterstrain) |
| <img src="/readme/hem_2_neg.jpg" height="200" width="300" > | <img src="/readme/hem_7_pos.jpg" height="200" width="300" >  |












Feedback
==========
Please send me your feedback at sandipsahajoy@ualberta.ca

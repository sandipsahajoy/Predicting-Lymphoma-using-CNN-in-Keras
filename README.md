# Predicting-Lymphoma-using-CNN-in-Keras
Context
==========
#### Classifying histopathology slides of Lymphoma as malignant or benign using CNN

<img src="/readme/inference/Slide2.JPG" height="450" width="800" >

About Lymphoma(Blood Cancer)
==========
### What is lymphoma?  
The lymph system is a series of lymph nodes and vessels that move lymph fluid through the body. Lymph fluids contain infection-fighting white blood cells. Lymph nodes act as filters, capturing and destroying bacteria and viruses to prevent infection from spreading.  
While the lymph system typically protects your body, lymph cells called lymphocytes can become cancerous. The names for cancers that occur in the lymph system are lymphomas.
Doctors classify more than 70 cancer types as lymphomas. Lymphomas can affect any portion of the lymphatic system, including:
* bone marrow
* thymus
* spleen
* tonsils
* lymph nodes  

**Doctors typically divide lymphomas into two categories:** 
 * Hodgkin’s lymphoma
 * non-Hodgkin’s lymphoma (NHL).

### What are the causes of lymphoma?
Cancer is the result of uncontrolled cell growth. The average lifespan of a cell is brief, and then the cell dies. In people with lymphoma, however, the cell thrives and spreads instead of dying. It’s unclear what causes lymphoma, but a number of risk factors are connected with these cancers.

### What are risk factors for lymphoma?
Most diagnosed lymphoma cases have no known cause. However, some people are considered higher risk.
* **Non-Hodgkin’s lymphoma risk factors**
	* **Immunodeficiency:** This could be due to a weak immune system from human immunodeficiency virus (HIV) or AIDs, or taking an immune system-suppressing drug after an organ transplant.
	* **Autoimmune disease:** People with certain autoimmune disease, such as rheumatoid arthritis and celiac disease, have an increased risk for lymphoma.
	* **Age:** Lymphoma is most common in people over 60. However, some types are more common in children and infants.
	* **Sex:** Women are more likely to develop some particular types of lymphoma, and men are more likely to develop other types.
	* **Ethnicity:** White Americans in the United States are more likely to develop some types of lymphoma than African-Americans or Asian-Americans.
	* **Infection:** People who have had infections such as the human T-cell leukemia/lymphotropic virus (HTLV-1), Heliobacter pylori, hepatitis C, or the Epstein-Barr virus (EBV) are associated with an increased risk.
	* **Chemical and radiation exposure:** Those exposed to chemicals in pesticides, fertilizers, and herbicides are also at increased risk. Nuclear radiation can also increase risks for developing NHL.
	* **Body size:** Obesity has been connected to lymphoma as a possible risk factor, but more research is needed to understand this possible risk factor.

* **Hodgkin’s lymphoma risk factors**
	* **Age:** More cases are diagnosed in people between the ages of 20 and 30, and in people over 55.
	* **Sex:** Men are more likely than women to develop this type of lymphoma.
	* **Family history:** If asibling is diagnosed with this type of cancer, your risk for also developing it is higher.
	* **Infectious mononucleosis:** An EBV infection can cause mononucleosis. This infection can increase the risk for lymphoma.
	* **Affluence:** Individuals that come from a background with a higher socioeconomic status have a greater risk for this type of cancer.
	* **Immunodeficiency:** Individuals with HIV have a greater risk for developing lymphoma.



### How is lymphoma diagnosed?
A biopsy typically is taken if a doctor suspects lymphoma. This involves removing cells from an enlarged lymph node. A doctor known as a hematopathologist will examine the cells to determine if lymphoma cells are present and what cell type they are. If the hematopathologist detects lymphoma cells, further testing can identify how far the cancer has spread. These tests can include a chest X-ray, blood testing, or testing nearby lymph nodes or tissues. Imaging scans, such as a computed tomography (CT) or magnetic resonance imaging (MRI) scans may also identify additional tumors or enlarged lymph nodes.

### What are the types of lymphoma?
The two major lymphoma types are Hodgkin’s lymphoma and non-Hodgkin’s lymphoma (NHL). A pathologist in the 1800s named Dr. Thomas Hodgkin identified the cells in what is now called Hodgkin’s lymphoma. Those with Hodgkin’s lymphoma have large cancerous cells called Reed-Sternberg (RS) cells. People with NHL don’t have these cells.

### Non-Hodgkin’s lymphoma
According to the Leukemia & Lymphoma Society (LLS), NHL is three times more common than Hodgkin’s lymphoma.Many lymphoma types fall under each category. Doctors call NHL types by the cells they affect, and if the cells are fast- or slow-growing. NHL forms in either the B-cells or T-cells of the immune system. According to LLS, most NHL types affect B-cells. Learn more about this type of lymphoma, who it affects, and where it occurs. Types include:
* **B-cell lymphoma (85% NHL case)** 
>Diffuse large B-cell lymphoma (DLBCL) is the most aggressive type of NHL. This fast-growing lymphoma comes from abnormal B cells in the blood. It can be cured if treated, but if left untreated, it can lead to death. The stage of DLBCL helps determine your prognosis. Read more about the stages and how this lymphoma is treated.
* **T-cell lymphoma**
>T-cell lymphoma is not as common a B-cell lymphoma; only 15 percent of all NHL cases are this type. Several types of T-cell lymphoma exist. Learn more about each one, what they cause, and who is more likely to develop them.
* **Burkitt’s lymphoma**
>Burkitt’s lymphoma is a rare type of NHL that is aggressive and most common in people with compromised immune systems. This type of lymphoma is most common in children in sub-Saharan Africa, but it does occur in other parts of the world. Learn more about this rare type of non-Hodgkin’s lymphoma.
* **Follicular lymphoma**
>One in 5 lymphomas diagnosed in the United States are follicular lymphoma. This type of NHL, which starts in the white blood cells, is most common in older individuals. The average age of diagnosis is 60. This lymphoma is also slow-growing, so treatments begins with watchful waiting. Read more about this strategy.
* **Mantle cell lymphoma**
>This aggressive form of lymphoma is rare — only about 6 percent of NHL cases are this type. Mantel cell lymphoma is also more commonly diagnosed at a later stage, and it usually occurs in or involves the gastrointestinal tract or bone marrow. Discover the risk factors and symptoms of mantle cell lymphoma.
* **Primary mediastinal B cell lymphoma**
>This subtype of B-cell lymphoma accounts for almost 10 percent of DLBCL cases. It predominantly affects women in their 20s and 30s.
* **Small lymphocytic lymphoma**
>Small lymphatic lymphoma (SLL) is a type of slow-growing lymphoma. The cancer cells of SLL are found mostly in the lymph nodes. SLL is identical to chronic lymphocytic leukemia (CLL), but with CLL, the majority of cancer cells are found in the blood and bone marrow.
* **Waldenstrom macroglobulinemia(lymphoplasmacytic lymphoma)**
>Lymphoplasmacytic lymphoma (LPL) is a rare type of cancer that accounts for just 1 to 2 percent of all lymphomas. It mostly affects older adults. Waldenstrom macroglobulinemia is a subtype of LPL. It causes the abnormal production of antibodies. Many people with LPL have anemia; read more about other common symptoms and risk factors.

### Hodgkin’s lymphoma
Hodgkin’s lymphomas typically start in B-cells or immune system cells known as Reed-Sternberg (RS) cells. While the main cause of Hodgkin’s lymphoma is not known, certain risk factors can increase your chances of developing this type of cancer. Learn what these risk factors are. Hodgkin’s lymphoma types include:
* **Lymphocyte-depleted Hodgkin’s disease**
>This rare, aggressive type of lymphoma occurs in about 1 percent of lymphoma cases, and it’s most commonly diagnosed in individuals in their 30s. In diagnostic tests, doctors will see normal lymphocytes with an abundance of RS cells.
Patients with a compromised immune system, such as those with HIV, are more likely to be diagnosed with this type of lymphoma.
* **Lymphocyte-rich Hodgkin’s disease**
>This type of lymphoma is more common in men, and it accounts for about 5 percent of Hodgkin’s lymphoma cases. Lymphocyte-rich Hodgkin’s disease is typically diagnosed at an early stage, and both lymphocytes and RS cells are present in diagnostic tests.
* **Mixed cellularity Hodgkin’s lymphoma**
>Like with lymphocyte-rich Hodgkin’s disease, mixed cellularity Hodgkin’s lymphoma contains both lymphocytes and RS cells. It’s more common — almost a quarter of Hodgkin’s lymphoma cases are this type — and it’s more prevalent in older adult men.
* **Nodular lymphocyte-predominant Hodgkin’s disease**
>Nodular lymphocyte-predominant Hodgkin’s disease (NLPHL) type of Hodgkin’s lymphoma occurs in about 5 percent of lymphoma patients, and it’s characterized by an absence of RS cells.
NLPHL is most common in people between the ages of 30 and 50, and it’s more common in males. Rarely, NLPHL can progress or transform into a type of aggressive NHL.
* Nodular sclerosis Hodgkin’s lymphoma
>This common type of lymphoma occurs in 70 percent of Hodgkin’s cases, and it’s more common in young adults than any other group. This type of lymphoma occurs in lymph nodes that contain scar tissue, or sclerosis.

Specimen to Dataset
==========
A total of 113 lymphomas (19 BL, 77 DLBCL, 6 intermediate between BL and DLBCL, and 11 unclassiﬁed aggressive B-cell lymphomas) diagnosed between 2010 and 2015 with known MYC status were selected. MYC IHC stains were produced in 2014 and 2015. All specimens had been ﬁxed in formalin (37% formaldehyde in aqueous solution) and embedded in paraﬃn. Although a small group of cases (B20%) was studied retrospectively, all cases in this analysis were stained utilizing freshly cut thin sections.

The dataset consisted of 4 types of 113 whole mount slide images(2560x1920) of Lymphoma specimens scanned at 20x. From each type of master image, around 42,750 child patches of size 100 x 100 were extracted (roughly 23,275 negative and 19,475 positive). 

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

Training & Evaluation
==========
The whole process is divided into 10 TestRuns to assure performance consistency of the models. 10 testruns are performed for each model where they are trained and evaluated on different train-test dataset generated from shuffled raw set of master images.

Size of trainset is 90x4 and testset is 23x4 out of 113x4 master images. 113 mother images of a type is shuffled, then randomly 90 images of that type along with other 3 types holding same patientID are selected for trainset(90x4).

First, two different model architectures are compared on the basis of performance on just type-0(MYC IHC) master image.

| Benign(-)  | Malignant(+)|
|------------|-------------|
| MYC IHC |
| <img src="/readme/2_neg.jpg" height="200" width="250" > | <img src="/readme/7_pos.jpg" height="200" width="250" >  |

<img src="/readme/inference/Slide3.JPG" height="450" width="800" >
<img src="/readme/inference/Slide5.JPG" height="450" width="800" >















Feedback
==========
Please send me your feedback at sandipsahajoy@ualberta.ca

Reference
==========
1. https://www.ncbi.nlm.nih.gov/pubmed/27093450

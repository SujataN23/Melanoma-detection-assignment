# Melanoma Detection Assignment
> Problem statement: To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC).
- All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.
- The data set contains the following diseases:
1. Actinic keratosis
2. Basal cell carcinoma
3. Dermatofibroma
4. Melanoma
5. Nevus
6. Pigmented benign keratosis
7. Seborrheic keratosis
8. Squamous cell carcinoma
9. Vascular lesion
### Sample Input Images
<img width="623" alt="image" src="https://github.com/user-attachments/assets/44e0a55b-2a01-4d39-a6e7-d01e631573d8">

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions

### Output after training last model
<img width="757" alt="image" src="https://github.com/user-attachments/assets/a2daeec0-c0cb-4d5c-b391-c20e39926843">


- The model achives a high training accuracy approching 0.95 so it learn well on training data.
- The validation accuracy increases in the first few epochs it shows model is learning useful patterns from the data.
- The training loss consistently decreasing is shows model minimizing errors on training data.
- The validation loss decreases at strating is shows model generalizes well on unseen data in easrly stage

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- pandas - 2.1.4
- numpy - 1.24.3
- matplotlib - 3.7.2
- keras - 3.5.0
- seaborn - 0.13.2
- tensorflow - 2.17.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Contact
Created by [@SujataN23] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->

# Melanoma_Detection_Assignment
> To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Create CNN based model and train

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- First Model : Shows overfitting as the traning accuracy is higher than that of validation data and loss is very high for validation data.
loss: 0.4826, accuracy: 0.8304, val_loss: 2.0570, val_accuracy: 0.5391
- CNN model with data augmentation: Shows Underfitting with same level of losses and accuracy of train and validation data.
loss: 1.3687, accuracy: 0.4922, val_loss: 1.4934, val_accuracy: 0.4765
- CNN after rectifying the class imbalance: Result has improved really well and it has 88% validation accuracy and 96% accuracy and loss has grown down.
loss: 0.1030, accuracy: 0.9582, val_loss: 0.4498, val_accuracy: 0.8838

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- pathlib
- tensorflow
- matplotlib
- numpy
- pandas
- PIL
- Augmentor

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This project was assignment of Upgrade ML and AI course 
- This project is based on CNN Model


## Contact
Created by [@ReemaRani2709] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
# Skin-Cancer-Detection
A skin cancer detection model built using convolutional neural networks Resnet50. 

## Abstract
#### Background
Skin cancer is a common form of cancer, and early detection increases the survival rate by a very large extent.

#### Objective
To build deep learning model to detect skin cancer by classifying a image to be either benign or malignant.

#### Methods
A skin cancer detection deep learning algorithm that takes in photos and classifies them as benign or malignant lesions. The TensorFlow framework is used to build the model using the Resnet50 model and the ISIC archive dataset.

#### Results
The deep learning models built here are tested on standard datasets, and the metric area under the curve of 84% was observed with a training acuuracy of 99%.

#### Conclusions
A practitioner can use the model to quickly predict skin cancer and then move forward with the treatment accordingly.

## Introduction
Skin cancer is a dangerous and widespread disease. Each year there are approximately 5.4 million new cases of skin cancer are recorded in USA alone. The global statistics are equally alarming. The survival rate is less than 14% if diagnosed in later stages. However, if the skin cancer is detected at early stages then the survival rate is nearly 97%. This demands the early detection of skin cancer. The aforementioned model can be used as an assistance to the dermatologists around the world to get better understanding of the patient's condition.

It is found that a skilled dermatologist usually follows a series of steps, starting with naked eye observation of suspected lesions, then dermoscopy (magnifying lesions microscopically) and followed by biopsy. This would consume time and the patient may advance to later stages. Moreover accurate diagnosis is subjective, depending on the skill of the clinician. It is found that the best dermatologist has an accuracy of less than 80% in correctly diagnosing the skin cancer. Adding to these difficulties, there are not many skilled dermatologists available globally in public healthcare.

In this model, an augmented assistance to the dermatologist is provided using deep learning. The essence of the approach is that a computer is trained to determine the problem by analyzing the skin cancer images. The average accuracy of diagnosis using this model is found to be approximately 84%. The machine assisted diagnosis presented here overcomes the problem of delay, accuracy, and scarcity of dermatologists in public health.

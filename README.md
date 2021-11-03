# Skin-Cancer-Detection
A skin cancer detection model built using convolutional neural networks Resnet50. 

## Abstract
#### Background
Skin cancer is a common form of cancer, and early detection increases the survival rate by a very large extent.

#### Objective
To build deep learning model to detect skin cancer by classifying a image to be either benign or malignant.

#### Methods


#### Results
The deep learning models built here are tested on standard datasets, and the metric area under the curve of 84% was observed with a training acuuracy of 99%.

#### Conclusions
A practitioner can use the model to quickly predict skin cancer and then move forward with the treatment accordingly.

## Introduction
Skin cancer is a dangerous and widespread disease. Each year there are approximately 5.4 million new cases of skin cancer are recorded in USA alone. The global statistics are equally alarming. The survival rate is less than 14% if diagnosed in later stages. However, if the skin cancer is detected at early stages then the survival rate is nearly 97%. This demands the early detection of skin cancer. The aforementioned model can be used as an assistance to the dermatologists around the world to get better understanding of the patient's condition.

It is found that a skilled dermatologist usually follows a series of steps, starting with naked eye observation of suspected lesions, then dermoscopy (magnifying lesions microscopically) and followed by biopsy. This would consume time and the patient may advance to later stages. Moreover accurate diagnosis is subjective, depending on the skill of the clinician. It is found that the best dermatologist has an accuracy of less than 80% in correctly diagnosing the skin cancer. Adding to these difficulties, there are not many skilled dermatologists available globally in public healthcare.

In this model, an augmented assistance to the dermatologist is provided using deep learning. The essence of the approach is that a computer is trained to determine the problem by analyzing the skin cancer images. The average accuracy of diagnosis using this model is found to be approximately 84%. The machine assisted diagnosis presented here overcomes the problem of delay, accuracy, and scarcity of dermatologists in public health.

Studies suggest that in the area of skin cancer detection and image classification, there exists a plethora of research papers. A detailed survey of these methods is available in Refs. [1,7,8]. Each of these papers [1,7,8] used the then available state-of-art methods and claim performance improvements. The popular methods used for image classifications vary from application of decision tree algorithms [9,10] Bayesian classifiers [[11], [12], [13]], support vector machines [8,14], to a variety of Artificial Intelligence based approaches [15,16]. However a common theme in all these papers is that they are made to appear as a job of specialists in the domain of computers and software engineering. An essential level of programming expertise in computer languages like Java, R, and Python is indeed required to build any of these diagnostic models [[17], [18], [19]]. In this paper, we address methods of developing deep learning based image classification models for identification of skin cancer, without having prior programming knowledge. The main objectives of this paper are:
1
To enable researchers and practitioners to develop deep learning models by simple plug and play art.

2
To classify the cell images and identify Cancer with an improved degree of accuracy using deep learning.

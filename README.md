# Covid-19 Detection using Convolutional Neural Network

## Introduction:
The coronavirus disease (COVID-19) is a global pandemic disease caused by the SARS-CoV-2 virus. Globally, over 400 million confirmed cases since the first reported case in November 2019, while the mortality exceeded 5 million death tolls. The Covid-19 is an infectious disease that spreads fast from an infected person through their mouth and nose. Most of the cases are mild to moderate; however, people who developed severe symptoms or death are older or have medical issues.

The main diagnosis methods (approaches) to detect the virus are Reverse transcription-polymerase chain reaction (RT-PCR), Computed Tomography (CT) and Chest X-ray, in addition to the pneumonia symptoms. Medical centres hold an enormous amount of images database that have been collected through X-ray and CT. Therefore, the fast and early detection of the disease can support in controlling the COVID-19 spread.

On the other hand, computer vision is a trending concept that plays a significant role in daily life, from online shopping to assisting doctors and medical providers in diagnosing. Computer vision algorithms benefit from the Convolutional neural network (CNN), a type of deep learning that contributes to automating the image classification, which plays a role in early detecting the disease. The network inputs are images, while the output is to classify image features. Many companies such as Google, Microsoft and many others benefit from using CNN and working toward novel designs.


## Dataset Description:
The X-ray images database was obtained from Kaggle called COVID-19 Radiography Database. A team of researchers developed this database in addition to other collaborators. It was collected from various sources such as the Italian Society of Medical and Interventional Radiology (SIRM) COVID-19 Database, over 40 publications, Chest X-Ray Images (pneumonia) database and Novel Corona Virus 2019 Dataset.

The dataset is publicly available to be used for academic purposes and can be accessed from the following link (https://www.kaggle.com/datasets/tawsifurrahman/covid19-radiography-database).

The database consists of four classes COVID, Lung_Opacity, Normal and Viral Pneumonia. Each consists of 3616, 6012, 10.2k and 1345 files. The COVID and Normal files were used in this coursework, with just 2000 images in each category. Then to obtain balanced classes, both Normal and COVID were split into 1000 train, 500 validation and 500 test sets.

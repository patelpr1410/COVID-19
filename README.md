

The COVID-19 pandemic continues to have a devastating effect on the health and well-being of the global population.  A critical step in the fight against COVID-19 is effective screening of infected patients, with one of the key screening approaches being radiology examination using chest radiography.  It was found in early studies that patients present abnormalities in chest radiography images that are characteristic of those infected with COVID-19.  Motivated by this and inspired by the open source efforts of the research community, in this study we introduce COVID-Net, a deep convolutional neural network design tailored for the detection of COVID-19 cases from chest X-ray (CXR) images that is open source and available to the general public. To the best of the authors' knowledge, COVID-Net is one of the first open source network designs for COVID-19 detection from CXR images at the time of initial release.  We also introduce COVIDx, an open access benchmark dataset that we generated comprising of 13,975 CXR images across 13,870 patient patient cases, with the largest number of publicly available COVID-19 positive cases to the best of the authors' knowledge.  Furthermore, we investigate how COVID-Net makes predictions using an explainability method in an attempt to not only gain deeper insights into critical factors associated with COVID cases, which can aid clinicians in improved screening, but also audit COVID-Net in a responsible and transparent manner to validate that it is making decisions based on relevant information from the CXR images.  **By no means a production-ready solution**, the hope is that the open access COVID-Net, along with the description on constructing the open source COVIDx dataset, will be leveraged and build upon by both researchers and citizen data scientists alike to accelerate the development of highly accurate yet practical deep learning solutions for detecting COVID-19 cases and accelerate treatment of those who need it the most.


## Requirements

The main requirements are listed below:

* Tested with Tensorflow
* OpenCV 
* Python 
* Numpy
* Scikit-Learn
* Matplotlib

Additional requirements to generate dataset:

* Pandas
* Jupyter

 


  

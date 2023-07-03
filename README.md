# BG-CNN-for-DC-Motor-FDI
 BG-CNN: A Hybrid Fault Diagnosis Method for Improved Fault Isolation. This repository presents the BG-CNN method, a novel approach that combines the Bond-Graph technique with Convolutional Neural Networks (CNNs) for efficient fault isolation.

 ## Data

The data used in this project is from the [ALL_DC_motor_Data](https://github.com/mohan696matlab/BG-CNN-for-DC-Motor-FDI/tree/main/ALL_DC_motor_Data) folder, which contains 12 CSV files of DC motor signals under different fault conditions. 

 ## Code

The code for this project is divided into five Jupyter notebooks:

- [Part_1_Data_pre_prcessing.ipynb](https://github.com/mohan696matlab/BG-CNN-for-DC-Motor-FDI/blob/main/Part_1_Data_pre_prcessing.ipynb): This notebook contains the code for data pre-processing, such as loading, splitting, normalizing, and creating sliding windows of the data.
- [Part_2_CNN_Training_ARR_github.ipynb](https://github.com/mohan696matlab/BG-CNN-for-DC-Motor-FDI/blob/main/Part_2_CNN_Training_ARR_github.ipynb): This notebook contains the code for training and testing a convolutional neural network (CNN) model using the ARR signals as input.
- [Part_3_HyperParam_Tuning_github.ipynb](https://github.com/mohan696matlab/BG-CNN-for-DC-Motor-FDI/blob/main/Part_3_HyperParam_Tuning_github.ipynb): This notebook contains the code for hyperparameter tuning of the CNN model using Bayesian optimization.
- [Part_4_NumberOfLabels.ipynb](https://github.com/mohan696matlab/BG-CNN-for-DC-Motor-FDI/blob/main/Part_4_NumberOfLabels.ipynb): This notebook contains the code for analyzing the effect of the number of labels on the performance of the CNN model.
- [Part_5_Comparision.ipynb](https://github.com/mohan696matlab/BG-CNN-for-DC-Motor-FDI/blob/main/Part_5_Comparision.ipynb): This notebook contains the code for comparing the CNN model with other baseline models, such as support vector machine (SVM), random forest (RF), and multilayer perceptron (MLP).

## Dependencies
The code is written in Python and uses libraries such as pandas, numpy, matplotlib, seaborn, sklearn, tensorflow, keras, and bayesian_optimization.

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/mohan696matlab/BG-CNN-for-DC-Motor-FDI/blob/main/LICENSE) file for details.

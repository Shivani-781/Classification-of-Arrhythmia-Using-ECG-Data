# Classification-of-Arrhythmia-Using-ECG-Data
Arrhythmia is a cardio-vascular disease, which when not treated well before time could lead to serious health issues in patients. An early diagnosis of this life-threatening disease would help save the lives of millions of people around us. 

In this study, an idea is proposed to classify patients into one of the sixteen classes, in which one class represents the case of normal people or those who do not have the disease and the other fifteen classes represent ECG records of various subtypes of arrhythmias. This study is carried out on the dataset taken from the University of California at Irvine Machine Learning (UCI ML) Data Repository.  This data set contains huge amount of feature dimensions, which included the records of ECG signals. These variables are reduced using dimensionality reduction techniques. 

In order to classify, various algorithms such as K-Nearest Neighbors (KNN), Logistic Regression, Decision Tree, Random Forest, Linear SVM as well as Kernelized SVM are employed over original data to detect the presence or absence of arrhythmias as well as to classify them into one of the available classes. The accuracies are then improved by using Principal Component Analysis (PCA) over the original dataset. The models are then evaluated and compared using their accuracy and recall values. 

The results showed that on applying PCA over the data, Kernelized SVM outperforms the other classifiers used with an accuracy rate of 80.21%.

# fetal_distress_detection

Cardiotocography (CTG) is a technique which monitors and determines the level of fetal distress. Even though, CTG is mostly used for monitoring fetus health, the presence of high number of false positive results in inappropriate surgical delivery and delayed intervention. The paper aims to determine how CTG data can be used to detect fetal distress using machine learning and deep learning models. The CTG data is acquired from CTU-UHB Database, from which the Fetal heart rate (FHR) and Uterine Contractions (UC) signals are extracted. After the extraction, the signals are resampled and preprocessed. The study concentrated on finding the important combinations of neonatal characteristics, such as umbilical cord pH and Apgar5 (5-minute) score, with optimum thresholds for classifying the samples accurately. Furthermore, to address challenges associated with small dataset size and class imbalance, we apply data augmentation. Various classifiers, such as Support Vector Machine (SVM), Random Forest (RF), and Convolutional Neural Network (CNN) are used, and they are assessed in terms of accuracy, precision, recall and f1-score. Experimental results reveal that CNN achieves the highest accuracy of 99.5%.

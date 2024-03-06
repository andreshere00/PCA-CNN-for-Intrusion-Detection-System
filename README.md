# PCA-CNN-for-Intrusion-Detection-System
PCA-CNN-based Intrusion Detection System for the subject "Neural Networks and Statistical Learning" for the Master's Degree in Statistical &amp; Computational Information Processing (Universidad Complutense de Madrid - Universidad Politécnica de Madrid)

In the data era, security and privacy have become relevant concerns due to the increasing sophistication and increase in cyberattacks. In this context, one of the elements most affected by this type of attacks are IoT (Internet of Things) devices, for which numerous ways to secure them have been investigated. Thus, this work aims to provide a solution to the problem of intrusion detection in IoT devices.

![Architecture diagram](methodology_diagram.svg)

After completing all the previous methodology, it is found that the best model is given by the following hyperparameters: ```{ 'filters': 128, 'kernel_size': 8, 'pool_size': 8, 'dense_units': 100, 'tuner_epochs': 40 }```.

As observed in Table Metrics, the metrics have correctly classified around 98% of the records for all cases. Therefore, it can be concluded that the analysis methodology, as well as the architecture design, are suitable for the proposed problem, and thus, an intrusion detection system for IoT environments has been successfully implemented.

Table: Metrics of the architecture performance (epoch 40)
| Metric     | Accuracy  | F1 Score | Precision | Recall  |
|------------|-----------|----------|-----------|---------|
| Score      | 0.9819    | 0.9821   | 0.9823    | 0.9821  |
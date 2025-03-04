# Distance-Based Classification using Facial Features

### Introduction

This project implements a distance-based classification model using facial features extracted from images. The model applies clustering techniques to classify faces based on hue and saturation values. It also incorporates template matching for facial recognition.

### Approach

Face Detection: Haar cascade classifiers are used to detect faces in an image.

Feature Extraction: Hue and saturation values are extracted from detected faces.

Clustering: K-Means clustering is applied to classify faces into groups.

Template Matching: A reference image is used to find the closest match in the dataset.

### Key Findings

Distance Metrics: Different distance metrics like Euclidean, Manhattan, and Mahalanobis play a crucial role in classification accuracy.

K-Means Clustering: Successfully groups faces based on color features, demonstrating its effectiveness in classification.

Bias-Variance Tradeoff in KNN: A low k value increases variance (overfitting), while a high k increases bias (underfitting).

Cross-Validation: Ensures the model generalizes well, preventing overfitting.

Real-World Applications: Face recognition, recommender systems, medical diagnosis, and anomaly detection benefit from distance-based classification.

### Conclusion

This project highlights the effectiveness of distance-based classification for facial recognition tasks. By leveraging clustering and template matching, it demonstrates practical applications in real-world scenarios. Future improvements could include deep learning-based face embeddings for enhanced accuracy.

### Plots

![Face Detection Example](Plots/1.png)
![Face Detection Example](Plots/2.png)
![Face Detection Example](Plots/3.png)
![Face Detection Example](Plots/4.png)

### Result

![Face Detection Example](result_classification.png)

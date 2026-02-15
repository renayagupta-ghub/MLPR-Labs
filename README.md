# Lab 5: Distance Metrics and Face Detection

### Aim
The objective of this lab was to understand how different distance measures operate and how they are applied in practical machine learning tasks. The exercise involved implementing distance functions such as Euclidean and Manhattan, using a Haar Cascade classifier for face detection, and experimenting with K-Means clustering.

---

### Method
1. **Face Detection:** Using the `cv2` library along with the `haarcascade_frontalface_default.xml` classifier, faces were detected in the `Plaksha_Faculty.jpg` image. Bounding boxes were drawn around each detected face.

2. **Distance Function Implementation:** Custom functions were created to compute:
   * **Euclidean Distance:** Measures the direct geometric distance between points.
   * **Manhattan Distance:** Computes the sum of absolute differences across dimensions.
   * **Hamming Distance:** Counts the number of mismatched positions in binary or string data.

3. **Clustering:** The `KMeans` algorithm from sklearn was applied to group data points according to similarity.

4. **Evaluation and Insights:** The role of cross-validation in improving model generalization was examined, along with how varying the number of neighbors in KNN influences the bias–variance trade-off.

---

### Conclusion
This lab demonstrated that selecting an appropriate distance metric is crucial, as it directly affects how algorithms interpret similarity within the data. An unsuitable metric can lead to poor classification or clustering performance. It was also observed that while Haar Cascade face detection is computationally efficient, it may fail under challenging conditions such as poor lighting or non-frontal poses. Overall, the lab reinforced the importance of managing the bias–variance balance to build models that generalize well without overfitting.

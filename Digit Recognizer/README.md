# Digit Recognizer

**Challange: get high accuracy as possible without using neural-networks (yet)**  
My attempts so far:  

| No. | Idea                                   | Accuracy |
|-----|----------------------------------------|----------|
| 1   | K-NN (using the elbow method)          | 96.63    |
| 2   | Random Forest (with adaptive depth)    | 96.12    |
| 3   | Blur (my simple version) + K-NN                            | 96.08    |
| 4   | SVM (rbg kernel with fixed parameters) | 97.44    |
| 5   | PCA (d=30) + SVM                       | 96.21    |
| 6   | Deskew (plain python code) + SVM       | 98.15    |
| 7   | Deskew + Blur + SVM (failed attempt)   | 8.99     |
| 8   | Deskew + Blur + SVM                    | 98.10    |

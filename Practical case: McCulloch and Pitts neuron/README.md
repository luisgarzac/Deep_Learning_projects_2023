Breast cancer diagnosis with Perceptron

This is a copy of the UCI ML Breast Cancer Wisconsin (Diagnostic) dataset (https://goo.gl/U2Uwz2).

The input features are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. They describe the characteristics of the cell nuclei present in the image.

The separation plane described above was obtained using the Multiple Surface Method Tree (MSM-T) method [K.P. Bennett, "Constructing a Decision Tree Classifier by Linear Programming." Proceedings of the 4th Midwest Artificial Intelligence and Cognitive Science Society, pp. 97-101, 1992], which is a classification method that uses linear programming to construct a decision tree. Relevant features were selected using an exhaustive search in the 1-4 feature space and 1-3 separation plane space.

The actual linear program used to obtain the separation plane in the three-dimensional space is described in: [K.P. Bennett and O.L. Mangasarian: "Robust Linear Programming Discrimination of Two Linearly Inseparable Sets", Optimization Methods and Software 1, 1992, 23-34].

This dataset is also available through the UW CS ftp server.

ftp ftp.cs.wisc.edu cd math-prog/cpo-dataset/machine-learn/WDBC/

### References

* W.N. Street, W.H. Wolberg and O.L. Mangasarian. Nuclear feature extraction for breast tumor diagnosis. IS&T/SPIE 1993 International Symposium on Electronic Imaging: Science and Technology, volume 1905, pages 861-870, San Jose, CA, 1993.
* O.L. Mangasarian, W.N. Street and W.H. Wolberg. Breast cancer diagnosis and prognosis via linear programming. Operations Research, 43(4), pages 570-577, July-August 1995.
* W.H. Wolberg, W.N. Street, and O.L. Mangasarian. Machine learning techniques to diagnose breast cancer from fine-needle aspirates. Cancer Letters 77 (1994) 163-171.

# MRI Brain Tumor Classification Using HOG Features Selected via Impurity Based Importances Measure

**Publisher:** International Journal of Electrical and Electronics Research

**Authors:** Yasser A. Nizamli; Anton Yu. Filatov

**Date of Conference:** November 2024

**DOI:** [10.37391/IJEER.120416](https://doi.org/10.37391/IJEER.120416)

**Abstract:**
MRI is considered the primary method for confirming the diagnosis of brain tumors and choosing the appropriate treatment. Automating the process of detecting brain tumors in MRI images using deep models has become a popular trend in the scientific research community. However, deep neural networks require a large volume of data to avoid overfitting, which is not ideally available. This is where handcrafted features come in handy. In this paper, we present an efficient approach for brain tumor classification that can outperform deep CNN models. In the proposed system, the histogram of oriented gradients algorithm is used to extract feature descriptors from brain MRI images. The extracted features are processed using a random forest algorithm, where each decision tree performs the task of evaluating feature importances via the impurity metric, while all estimators collaborate in selecting the effective feature set. Finally, the Fine KNN algorithm is used to classify the types of brain tumors based on the numerical features obtained. The presented model achieved a high-test accuracy of 99.35% with an F1-score of 99.30%, outperforming many deep models.

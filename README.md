# Adversarial-image-detection
A repository of jupyter notebooks on the paper **"Explainable AI for detection of adversarial machine learning via UMAP and open data"** on the MNIST and CIFAR datasets authored by Koroma A.S., Narteni S., Cambiaso E., & Mongelli M.
Attacking techniques like fast sign gradient methods, Carlini-Wagner method and projected gradient descent method are investigated by the embeddings of both legitimate and malicious MNIST and CIFAR dataset via UMAP for different dimension reduction. 


# Code usage
To generate the UMAP data for both FGSM and Carlini attacks, Install the adversarial robustness toolbox, UMAP and import all required libraries as in the jupyter notebooks. 
Load the trained CNN model. Generate the legitimate dataset via UMAP for 2D, 3D, 5D and 10D. Impliment the attack (FGSM/Carlini) to generate the malicious datasets for 2D, 3D, 5D and 10D. Then concatenate the generated ligitimate and and malicious datasets in a single .csv file.

**Metrics computation:** The decision tree classifier is used in the computation of metrics, important feature rankings and rules extraction.



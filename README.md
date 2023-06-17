# ml-project
For this project, machine-learning models are used to try and detect breast cancer based on
X-ray images. Tumours are difficult to see on X-ray images due to the anatomy of the breast,
thus micro-calcifications (MCs or micros) are used to detect breast cancer. MCs are white
calcium deposits that are easy to see on X-ray images, unlike tumours, and can be indicative
of cancer as there is a correlation between MCs and tumours. Malignant MCs are MCs that
are in the neighbourhood of tumours, while benign MCs are not.
</br>
The dataset I got for the project already contained the extracted features of the MCs, so no feature extracting was done by me. The first part consists of classifying the MCs individually, and the second part is trying to use the optimal model for classifying MCs and to then predict whether a patient has breast cancer.



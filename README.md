# Artificial Intelligence performance in Image-Based Ovarian Cancer Identification:

### Introduction:
- Accurate identification of `ovarian cancer (OC)` is of paramount importance in *clinical treatment success*. 
- `Artificial intelligence (AI)` is a potentially reliable assistant for the medical imaging recognition.
- This paper is the first systematic review
and `meta-analysis` specifically dedicated to AI systemperformance in the diagnosis of *Overian Cancer*


### Databases searched:
1. [The Medline](https://in.medlineasia.com/)
2. [Embase](https://www.elsevier.com/en-in/products/embase)
3. [IEEE](https://www.ieee.org/)
4. [PubMed](https://pubmed.ncbi.nlm.nih.gov/)
5. [Web of Science](https://mjl.clarivate.com/home)
6. [Cochrane Library](https://www.cochranelibrary.com/)

---
### Methods used:
-  Acceptable diagnostic performance was demonstrated in
subgroup analyses stratified by imaging modalities `(Ultrasound, Magnetic Resonance Imaging, or Computed Tomogra-
phy)`
- The binary diagnostic accuracy data were extracted to derive the
outcomes of interest: `sensitivity` **(SE)**, `specificity` **(SP)**, and `Area Under the Curve` **(AUC)**. 
- This study also includes meta-analyis
---
### What is Sensitivity and Specificity?
![Sensitivity_and_specificity](imgs/Sensitivity_and_specificity.png)
- `sensitivity` and `specificity` describe the accuracy of a test that reports the presence or absence of a medical condition. 
- `Sensitivity`**(true positive rate)** is the probability of a positive test result, conditioned on the individual truly being positive.
- `Specificity` **(true negative rate)** is the probability of a negative test result, conditioned on the individual truly being negative.

[more on sensitivity_and_specificity...](https://en.wikipedia.org/wiki/Sensitivity_and_specificity)

---
### ROG & AUC

ROG stands for Reciever Operator Graph. It is used to compare the different confusion matrics produced by taking different thresholds.

![ROG Example](imgs/ROG.png)

where, **True Positive Rate** is calculated by:

![ROG Example](imgs/true_pos.png)
&  True Negative Rate is calculated by:


Imp:
- really good video:
[ROC and AUC, Clearly Explained!](https://www.youtube.com/watch?v=4jRBRDbJemM)
- more info: [Google Developers](https://developers.google.com/machine-learning/crash-course/classification/roc-and-auc)
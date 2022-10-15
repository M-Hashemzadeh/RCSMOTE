# RCSMOTE: Range-Controlled Synthetic Minority Over-sampling Technique for handling the class imbalance problem

The Synthetic Minority Over-Sampling Technique (SMOTE) is one of the most well known methods to solve the unequal class distribution problem in imbalanced datasets. However, it has three shortcomings: 1) it may cause the over-generalization problem due to over-sampling of noisy samples, 2) over-sampling of uninformative samples, and 3) increasing the overlaps between different classes around the class boundaries. In this research, an improved SMOTE-based method, namely Range-Controlled SMOTE (RCSMOTE), which targets all three problems simultaneously, is proposed. In order to cope with the two first problems, a sample categorization scheme is applied to identify the minor samples that are proper for over-sampling. In order to mitigate the third problem, an improved sample generation process is proposed which generates the synthetic samples considering an accurately calculated safe range. This range is calculated based on the characteristics of the input data in order to provide us a safe over-sampling region for each dimension in the feature space. The extracted range is used to control the location of the new synthetic samples in data space and prevents the penetration of them into the majority class regions. Experiments conducted on various datasets, confirm that the RCSMOTE overcomes the above-mentioned problems of SMOTE.

The ImplementationSourceCodes.zip file includes the MATLAB implementation of the RCSMOTE algorithm presented in:

P. Soltanzadeh and M. Hashemzadeh, "RCSMOTE: Range-Controlled synthetic minority over-sampling technique for handling the class imbalance problem," Information Sciences, vol. 542, pp. 92-111, 2021/01/04/ 2021, doi: https://doi.org/10.1016/j.ins.2020.07.014.

# Condition and terms to use any sources of this project (Codes, Datasets, etc.):

1) Please cite the following paper:

P. Soltanzadeh and M. Hashemzadeh, "RCSMOTE: Range-Controlled synthetic minority over-sampling technique for handling the class imbalance problem," Information Sciences, vol. 542, pp. 92-111, 2021/01/04/ 2021, doi: https://doi.org/10.1016/j.ins.2020.07.014.

2) Please do not distribute the database or source codes to others without the authorization from Dr. Mahdi Hashemzadeh (Corresponding author).

Authors’ Emails: hashemzadeh[at]azaruniv.ac.ir (M. Hashemzadeh).

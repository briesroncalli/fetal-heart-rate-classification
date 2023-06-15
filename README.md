# fetal-heart-rate-classification
Cardiotocography (CTG) is a medical procedure used to monitor the fetal heart rate and uterine contractions during pregnancy, particularly during labor. It involves attaching sensors to the mother's abdomen to record the baby's heart rate and monitor uterine contractions, providing valuable information about the well-being of the fetus and the progress of labor. This notebook examines a dataset of measurements of fetal heart rate (FHR) and uterine contraction (UC) features on cardiotocograms classified by expert obstetricians to attempt to classify fetal state as normal, suspect or pathologic. The performance of various machine learning models and feature selection techniques are used to evaluate the best performing model.

## Data
Campos, D. and Bernardes, J.. (2010). Cardiotocography. UCI Machine Learning Repository. https://doi.org/10.24432/C51S4N.

A total of 2126 fetal cardiotocograms (CTGs) were automatically processed and the respective diagnostic features measured. The CTGs were also classified by three expert obstetricians and a consensus classification label assigned to each of them. Classification was both with respect to a morphologic pattern (A, B, C. ...) and to a fetal state (N, S, P). Therefore the dataset can be used either for 10-class or 3-class experiments. This project concentrates only on the 3-class classification problem.

#### Features
LB - FHR baseline (beats per minute)  
AC - # of accelerations per second  
FM - # of fetal movements per second  
UC - # of uterine contractions per second  
DL - # of light decelerations per second  
DS - # of severe decelerations per second  
DP - # of prolongued decelerations per second  
ASTV - percentage of time with abnormal short term variability  
MSTV - mean value of short term variability  
ALTV - percentage of time with abnormal long term variability  
MLTV - mean value of long term variability  
Width - width of FHR histogram  
Min - minimum of FHR histogram  
Max - Maximum of FHR histogram  
Nmax - # of histogram peaks  
Nzeros - # of histogram zeros  
Mode - histogram mode  
Mean - histogram mean  
Median - histogram median  
Variance - histogram variance  
Tendency - histogram tendency  
CLASS - FHR pattern class code (1 to 10)  
NSP - fetal state class code (N=normal; S=suspect; P=pathologic)  

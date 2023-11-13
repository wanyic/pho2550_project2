# php2550_project2
Bronchopulmonary Dysplasia (BPD) is the most common complication of prematurity with the severe form affecting 10,000 - 15,000 infants each year. There are 4 grades to BPD, Mild (Grade 1): room air at 36 weeks of Post Menstrual Age (PMA); Moderate (Grade 3) < 30% oxygen at 36 weeks of PMA; Severe (Grade 4) >30% oxygen at 36 weeks of PMA or on Positive Pressure Ventilation (PPV); Very Severe (Grade 4): Death between 14 days and 36 weeks (NHLBI 2001). Within these levels of BPD severity, patients with Grade 3 BPD depends on a ventilator at 36 weeks corrected gestational age and, 75% of these patients will remain on a ventilator when they are discharged from the hospital while 25% will not need a ventilator. When discharged from the hospital on ventilator, a patient needs tracheostomy which is a surgical hole in the patient's neck that allows them to be hooked up with a tracheostomy tube or ventilator and this does not need to be permanent (McKinney and Levin). However,  performing a tracheostomy comes with benefits as well as associated risks. Some benefits of a tracheostomy includes providing a stable airway for the patient, improving patient's age-appropriate interactions, improving patient's participation in developmental care and more importantly, tracheostomy performed within 4 months of age is associated with improved outcomes (Mckinney and Levin). The associated risks can included: increased risk of death compared to no tracheostomy, accidental decannulation that can lead to death, and increased rates of infection from skin, trachea, and lungs.

Given the advantages and disadvantages of performing a tracheostomy, it is important to understand and identify which groups of patients really needs tracheostomy. It is also important to find out the ideal time frame to refer a patient for tracheostomy. The goal of this project, is to develop a statistical model using clinical data at 36 and 44 weeks PMA to predict the need for tracheostomy or death prior to discharge.

The required R packages for this project are:
* tidyverse
* mice, used for multiple imputation
* gtsummary
* dplyr
* glmnet, used to perform Lasso variable selection 
* leaps
* tableone, to output markdown format tables
* DescTools, to calculate evaluation metrics Brier Score
* Metrics, to calculate evaluation metrics RMSE/MAE
* pROC, to calculate evaluation metrics AUC and ROC curves
* GGally, for correlations and scatterplots between variables

The figure folder includes all the figures produced in this project.
The full codes are available in the qmd file.

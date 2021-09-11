# Calculating-change-from-baseline-in-R

The details of the codeset and plots are included in the attached Adobe Acrobat reader (.pdf) file in this repository. 
You need to download the same to view the contents. There are referrals to other contents in BLUE colour also to follow.

The dataset is coming from : https://www.psiweb.org/sigs-special-interest-groups/visualisation/welcome-to-wonderful-wednesdays

As a statistical programmer working on clinical trials data I frequently have to calculate change from baseline. In clinical trials baseline is typically defined as the last measurement prior to a clinical trial subject receiving any study drug. Change from baseline is frequently calculated for laboratory measurements, e.g. hemoglobin concentration in blood.

SAS is still the standard used to program datasets in the pharmaceutical industry but R is catching up. Recently, I derived change from baseline for the first time in R. Using my beloved {dplyr} package this was straightforward to do.

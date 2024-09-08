

### MULTI-OMIC MACHINE LEARNING PREDICTOR OF BREAST CANCER
#### THERAPY RESPONSE [2]
#### Authors: Olabode Kaosara Omowunmi (@TheResearchNerd), Rachael Oluwakamiye Abolade
#### (@Oluwakamiye), Otuekong Emmanuel (@Otuekong), Oluwatobi Ogundepo (@Oluwatobi)

### Introduction
Globally, breast cancer is the leading invasive cancer among women. It accounts for nearly one-
quarter of invasive cancers in women worldwide, and one-sixth of all female cancers.[1]
This research focuses on identifying the multi-omic features associated with breast cancer
therapy   response,   emphasizing   on   the   need   to   build   machine   learning   models   to   predict
pathology end points of cytotoxic therapy. [2]
The objective  of the research is to develop and validate a machine learning model that can
accurately   predict   the   pathological   complete   response   (PCR)   following   neoadjuvant
chemotherapy, a critical outcome for breast cancer patients.

### Overview of the study design
![overview of stage 1 study design](https://media.springernature.com/full/springer-static/image/art%3A10.1038%2Fs41586-021-04278-5/MediaObjects/41586_2021_4278_Fig1_HTML.png?as=webp)

### Methodology
The study assembled a large and diverse cohort of breast cancer patients, ensuring a
representative sample for model development and validation.
Multi-omic   data   collection   was   employed  to   capture   comprehensive   genomic   and
transcriptomic   information   from   tumor   samples.   Additionally,   digital   pathology
techniques were used to analyze tumor morphology and cellular composition.
The researchers also extracted tumor mutational burden, immune cell infiltration, and
gene expression signatures associated with tumor biology and treatment response, from
the multi-omic data.
A gradient boosting algorithm was selected for model development, known for its ability
to handle complex relationships and non-linear interactions within the data.

### Results
The developed model demonstrated superior performance in predicting predicted a pathological
complete response (pCR) compared to existing methods, achieving an AUC of 0.87 in an
external validation cohort. This indicates that the model can accurately differentiate between
patients who are likely to achieve PCR and those who are less likely to respond to treatment.
In   addition,   the   model   identified   several   key   features   that   contributed   significantly   to   its
predictive power. These features included tumor mutational burden, immune cell infiltration, and
gene   expression   signatures   related   to   T-cell   dysfunction.   These   findings   provide   valuable nsights into the biological mechanisms underlying treatment response.
The research also suggests that the developed model could be used to identify patients who are
more likely to benefit from neoadjuvant chemotherapy, potentially leading to more personalized
treatment decisions and improved patient outcomes.

### Conclusion 
The challenges of the study include the sample size and the applicability of the findings to
different patient populations. However, the authors claim that the model's performance and the
identified key features will likely apply to a broader range of breast cancer patients.
It   is   recommended   that  the   model   should   be   expanded   to   include   additional   clinical   and
molecular   features,   exploring   its   applicability   to   other   cancer   types,   and   investigating   the 
potential for real-world implementation in clinical practice.

### References
1. Arnold M, Morgan E, Rumgay H, Mafra A, Singh D, Laversanne M, Vignat J, Gralow
JR, Cardoso F, Siesling S, Soerjomataram I. Current and future burden of breast cancer:
Global   statistics   for   2020   and   2040.   Breast.   2022   Dec;66:15-23.   doi:
10.1016/j.breast.2022.08.010.   Epub   2022   Sep   2.   PMID:   36084384;   PMCID:
PMC9465273.
2. Sammut SJ, Crispin-Ortuzar M, Chin SF, Provenzano E, Bardwell HA, Ma W, Cope W,
Dariush A, Dawson SJ, Abraham JE, Dunn J, Hiller L, Thomas J, Cameron DA, Bartlett
JMS, Hayward L, Pharoah PD, Markowetz F, Rueda OM, Earl HM, Caldas C. Multi- omic   machine   learning   predictor   of   breast   cancer   therapy   response.   Nature.   2022
Jan;601(7894):623-629. doi: 10.1038/s41586-021-04278-5. Epub 2021 Dec 7. PMID:
34875674; PMCID: PMC8791834.

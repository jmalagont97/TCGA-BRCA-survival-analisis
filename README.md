# TCGA-BRCA-survival-analisis

Triple-negative breast cancer (TNBC) is a particularly aggressive and complex subtype of breast cancer, which represents a significant challenge in current oncological medicine. Its mortality rate reaches 24% due to its intrinsic heterogeneity, which hinders the understanding of the disease and the planning of effective treatment strategies. In this context, a machine learning model, named “DenseSurvNet”, was developed and implemented, capable of estimating the survival curve of patients with TNBC from the analysis of histological features present in pathology images. Using a cohort of 1,097 breast cancer patients from The Cancer Genome Atlas (TCGA) project, a novel approach was formulated that integrates convolutional neural networks specialized in digital pathology and the Cox proportional hazards model, to learn features associated with TNBC prognosis from micromorphological patterns present in the multiple molecular subtypes of breast cancer. The proposed model achieves a concordance index of 0.73 ± 0.012, presenting a performance 22% above random capacity and 5% above tabular implementations, suggesting not only that “DenseSurvNet” has the potential to provide relevant information on the survival of TNBC cases; it also highlights the positive effect of a heterogeneous case set during model training. Finally, the patterns extracted by “DenseSurvNet” were analyzed, where it was identified that the presence of highly vascularized regions, tissues infiltrated by lymphocytic cells, and sections with adipose tissue are associated with the prognosis of the disease, improving the understanding of the biological mechanisms underlying the aggressiveness of the pathology.

Auth:

Msc. Juan Sebastian Malagón Torres - https://co.linkedin.com/in/juan-sebastian-malagón-torres-86039a164


Phd. Fabio Gonzalez Osorio - http://www.hermes.unal.edu.co/pages/Docentes/Docente.jsf?u=fagonzalezo


Phd. Angel Cruz Roa - https://sites.google.com/site/aacruzr/

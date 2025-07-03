# Thesis template 
This repository contains the LaTeX template used for writing and defending my PhD thesis (pdf included). It was designed to provide a clean, professional, and structured format for academic theses.

If you use or adapt it, please credit this repository by including a short mention in your acknowledgements or documentation. 

"This document is based on the LaTeX template developed by C. Jiménez-Mesa, available at https://github.com/crmn-jm/thesis_template/"

# Enhancing diagnostic accuracy in neuroimaging through machine learning: advancements in statistical classification and mapping
A PhD thesis by Carmen Jiménez-Mesa

# Abstract
In recent years, the application of artificial intelligence (AI) techniques in health and medicine, including neuroimaging, has grown exponentially. Neuroimaging plays a crucial role in studying the central nervous system and supporting clinical diagnosis through non-invasive examination of the human brain. Computer-aided diagnosis (CAD) systems have been developed to assist clinicians in this process by using pattern recognition and prediction capabilities. These systems, created through multidisciplinary collaboration, incorporate AI algorithms to improve diagnostic accuracy and reduce clinician workload. However, these systems face certain challenges, such as the lack of interpretability of AI models and the small sample sizes inherent in neuroimaging studies, which complicate system learning and performance.  Addressing these challenges is crucial for establishing CAD systems as a standard for clinical diagnostic support. 

This thesis focuses on exploring various machine learning (ML) approaches to enhance the accuracy and utility of CAD systems while ensuring optimal interpretability for clinical analysis. 

To enhance reliability, one approach involves tackling the \textit{curse of dimensionality} by reducing the number of features. The significance of feature selection and extraction stages is emphasised in the development of an optimised multiclass classification system. Additionally, validation methods implemented so far in neuroimaging studies are questioned. The viability of an upper-bounded resubstitution as a validation method is demonstrated through a non-parametric statistical inference framework, particularly suitable in studies with small sample sizes.  Moreover, the use of classical statistics in neuroimaging, which usually rely on assumptions that are frequently violated, is also questioned. To address this, a proposed data-driven approach for generating statistical inference maps is tested in brain disorders such as Alzheimer's Disease and Parkinson's Disease, and compared with a parametric approach. 

Regarding interpretability, two systems are designed to provide easily interpretable results for clinical experts. These systems place emphasis on the use of explainable AI techniques. One system focuses on analysing sulcal morphology in individuals with schizophrenia, while the other system proposes a method for detecting patterns in the Clock-Drawing Test to assess cognitive impairment.

In summary, this thesis demonstrates the utility of ML techniques in neuroimaging for brain mapping, feature detection, and classification. It explores the reliability and interpretability of CAD systems, identifies potential improvements, and emphasises the need for further research to develop techniques tailored to neuroimaging's unique conditions. This advancements will enable CAD systems to become a standard for clinical diagnostic support, ultimately improving the quality of life for patients through earlier and more accurate diagnoses.

Copyleft (cc) Carmen Jiménez-Mesa 

# License
Shield: [![CC BY-NC-ND 4.0][cc-by-nc-nd-shield]][cc-by-nc-nd]

This work is licensed under a
[Creative Commons Attribution-NonCommercial-NoDerivs 4.0 International License][cc-by-nc-nd].

[![CC BY-NC-ND 4.0][cc-by-nc-nd-image]][cc-by-nc-nd]

[cc-by-nc-nd]: http://creativecommons.org/licenses/by-nc-nd/4.0/
[cc-by-nc-nd-image]: https://licensebuttons.net/l/by-nc-nd/4.0/88x31.png
[cc-by-nc-nd-shield]: https://img.shields.io/badge/License-CC%20BY--NC--ND%204.0-lightgrey.svg

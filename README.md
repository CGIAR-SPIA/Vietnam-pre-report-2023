# Preliminary Insights into the Adoption Agricultural Innovations in Vietnam - Report Repository

Welcome to this repository. It houses material and reproducible codes that were used report documenting the adoption of agricultural innovations in Vietnam during the year 2022. The report is based on data collected by the [General Statistics Office](https://www.gso.gov.vn/en/homepage/) from the Vietnam Household Living Standards Survey (VHLSS) 2022 and provides insights into the adoption patterns of various agricultural innovations across the country, including rice traits identified using molecular markers, sustainable intensification practices and climate change adaptation options.

The report analysis can be reproduced by downloading the [analysis directory]((https://raw.githubusercontent.com/CGIAR-SPIA/Vietnam-pre-report-2023/main/datasets/) on a local machine and running the R scripts.

# Repository Contents

1.	Agricultural Innovations Stocktake: The [VN_Stocktake.xls](https://raw.githubusercontent.com/CGIAR-SPIA/Vietnam-pre-report-2023/main/VN_Stocktake.xlsx) Excel file documents the 79 agricultural innovations identified in Vietnam in 2000-2021. This stocktake provides a comprehensive overview of the innovations, aiding researchers and policymakers in understanding the innovation landscape. Innovations highlighted in grey (n=19) are believed to be adopted at scale, and thus were the subject of data collection efforts. You can find the glossary of key terms and references used in the stocktake on additional sheets of the document.
   
2. Training material (VHLSS 2022): SPIA’s presentation during VHLSS 2022 training of enumerators is named [VHLSS_22_training (VN)](https://raw.githubusercontent.com/CGIAR-SPIA/Vietnam-pre-report-2023/main/training/VHLSS_22_training (VN).pdf). A video that demonstrates the technique used for rice leaf sampling (VHLSS 2022) is available upon request in English and Vietnamese. It was shown during VHLSS enumerator training and made available to enumerators.
   
3. Training material (VHLSS 2023): The training presentation is named [VHLSS_23_training (VN)](https://raw.githubusercontent.com/CGIAR-SPIA/Vietnam-pre-report-2023/main/training/VHLSS_23_training (VN).pdf). Additionally, [Training_Cassava_DNA.pdf](https://raw.githubusercontent.com/CGIAR-SPIA/Vietnam-pre-report-2023/main/training/Training_Cassava_DNA.pdf) explain the Cassava sampling procedure to enumerator during the VHLSS 2023 training. These materials are valuable resources for researchers and practitioners involved in agricultural sampling.
   
4. Pilot Testing of the 1M5R Module: The [Pilot testing of the 1M5R module.html](https://raw.githubusercontent.com/CGIAR-SPIA/Vietnam-pre-report-2023/main/Pilot testing of the 1M5R module.html) file contains descriptive results from the pilot testing of the 1M5R (One Must Do, Five Reductions) instruments integrated into the VHLSS 2023. This valuable information sheds light on the methodological challenges for collecting data on Sustainable Intensification practices.
   
5. Variable Dictionary: The [VHLSS_22_variables.doc](https://raw.githubusercontent.com/CGIAR-SPIA/Vietnam-pre-report-2023/main/datasets/VHLSS_22_variables.doc) document provides a detailed dictionary of variables used in the analysis. It explains the meaning and context of each variable, enhancing the transparency of the research.
   
6. Datasets: The repository includes several datasets used for the analysis. These datasets relate VHLSS 2022 new data inclusions, shapefiles, rice QTL data, and weights. Modules are available in the published report in Appendix C. Dataset were anonymized and are available in the [datasets directory](https://raw.githubusercontent.com/CGIAR-SPIA/Vietnam-pre-report-2023/main/datasets/).
    
7. Analysis: The [analysis directory](https://raw.githubusercontent.com/CGIAR-SPIA/Vietnam-pre-report-2023/main/analysis/) contains R markdown documents used to generate the tables and figures presented in the report. These documents are well-documented and can be easily executed to reproduce the visualizations in the report.
•	VH22_Core_Results.Rmd reproduce the report core results. Its output are Table 4 Report.xls and VHLSS22_Analysis.doc
•	Rice_QTLs.Rmd generates province-level maps of QTL distribution (Rice-QTLs-by-province.pdf). It also generates the maps used in the report (Province_Markers_Maps.doc)
•	Self_elicitated_rice_traits reproduced the analysis comparing farmer's elicited traits with rice QTL markers (Self_elicitated_rice_traits.docx).
•	CSMaps.Rmd generates the maps and OLS anlaysis published in the report (CSMaps.docx)

# How to Use This Repository

To make the most of this repository, consider the following steps:

1.	Explore the Report: Start by reading the main [report](). It provides insights into the adoption patterns of various agricultural innovations across the country, including rice traits identified using molecular markers, sustainable intensification practices and climate change adaptation options.
   
3.	Understand Innovations: Study the [VN_Stocktake.xls](https://raw.githubusercontent.com/CGIAR-SPIA/Vietnam-pre-report-2023/main/VN_Stocktake.xlsx) file for a comprehensive understanding of the agricultural innovations identified in Vietnam.
   
5.	Learn from Pilot Testing: Explore the Pilot testing of the 1M5R module file to gain insights from the pilot testing of the 1M5R module.
   
7.	Watch Training Video: The Video_training_Rice_DNA.mp4 video and Training_Cassava_DNA.pdf explain the Cassava sampling demonstrate rice and cassava leaf sampling techniques, supporting enumerators in their work.
   
9.	Reproduce Analysis: The analysis directory contains R markdown documents that generate tables and figures. Download and execute these documents to recreate the report results, tables and visualizations.
    
11.	Access Datasets: The datasets directory contains datasets used for the analysis. You can use these datasets for further research and analysis.
    
Thank you for your interest in this repository. If you have any questions or feedback, please don't hesitate to reach out f.kosmowski@cgiar.org.


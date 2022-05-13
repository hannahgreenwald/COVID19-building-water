# COVID19-building-water
This site contains the raw data and R code corresponding to the research study on drinking water quality and bacterial communities in reduced-occupancy academic buildings during the COVID-19 pandemic (Greenwald et. al, 2022). 

Sample raw data is included as "Tap_Stagnation.xlsx". The "stagnation_data" tab includes information about sample collection and water quality data. The "stag_qPCR" tab includes raw qPCR data from every plate. 

Sequencing data has been deposited to NCBI SRA, PRJNA836918.

R code files were executed in Jupyter Lab. The file "stagnation_data_analysis_public.ipynb" contains the code to produce all figures and tables, except those reliant on bacterial sequencing data. The file " " is for processing of sequencing reads with DADA2. The file " " is for decontamination of sequencing reads. The file " " is for the generation of tables and figures related to bacterial amplicon sequencing. Files "", "", "", and "" should be run sequentially. 

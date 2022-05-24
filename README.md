# COVID19-building-water
This site contains the raw data and R code corresponding to the research study on drinking water quality and bacterial communities in reduced-occupancy academic buildings during the COVID-19 pandemic (Greenwald et. al, 2022). 

Sample raw data is included as "Tap_Stagnation.xlsx". The "stagnation_data" tab includes information about sample collection and water quality data. The "stag_qPCR" tab includes raw qPCR data from every plate. 

Sequencing data has been deposited to NCBI SRA, PRJNA836918.

R code files were executed in Jupyter Lab. Files "stagnation2022_16S_dada2_toshare.ipynb", "stagnation2022_16S_decontam_toshare.ipynb", and "stagnation2022_16S_analysis_toshare.ipynb" should be run sequentially. 

  1. The file "stagnation2022_analysis_toshare.ipynb" contains the code to produce all figures and tables, except those reliant on bacterial sequencing data. 
  2. The file "stagnation2022_16S_dada2_toshare.ipynb" is for processing of sequencing reads with DADA2. 
  3. The file "stagnation2022_16S_decontam_toshare.ipynb" is for decontamination of sequencing reads. 
  4. The file "stagnation2022_16S_analysis_toshare.ipynb" is for the generation of tables and figures related to bacterial amplicon sequencing. 

Data and code files should be downloaded and placed in the proper directories. Listed directories within the code files will then need to be changed to appropriate local directories. Uncomment sections of the code to install necessary packages. 

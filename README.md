
# Mapping of SNP
## Table of Contents
- Project Description
- Tools
- Project Structure
- Data analysis and Results
- Contact

## Project Description
### Inrtoduction
This project deals with the mapping of putative Single Nucleotide Polymorphisms (SNPs) that rescued the ssadh phenotype of Arabidopsis thaliana. The ssadh homozygous mutant showed abnorml phenotype. Ethylmethanesulfonate(EMS), a chemical mutagen, treatment of the ssadh mutant seeds induced thousands of random mutations in the genome. The EMS mutation rescued the ssadh phenotype almost to a wild type level. The question is which mutation/s is/are responsible for rescuing the ssadh phenotype. Selected EMS mutant lines named as L7D, L13J, L17J and L21H showed an improved phenotype compared to the ssash homozygous ssadh line. QTL analysis using bi-parental crosses (col-0 with Ler ecotypes, ssadh mutant is col-o background) showed that mutations at the lower arms of chromsome 2 and 5 are resposnsible for suppression of ssadh phenotype. The regions were identified using PCR based markers that distinguish between the two ecotypes (https://www.researchgate.net/publication/318793356_The_suppression_of_Arabidopsis_succinic_semialdehyde_dehydrogenase_SSADH_phenotype_by_using_ethyl_methane-sulfonate_mutagenesis_EMS). 
The genomic DNA from these four lines were extracted and genotyped using Next Generation Sequencing (NGS) technology. The SNPs in the regions was further charatcterized using SQL and Python codes to select putative mutations. 
### Project specific questions
- How many SNPs and INDELS (Insertions/Deletion) exist in the mapped region?
- Which mutations are located within the genic regions?
- Are there distinct mutations between the lines?
- Which type of mutation is most abundant in the region? C to T, G to A etc?

### Specific Objectives
- Identify putative mutations in the mapping region which can used for further functional characterization.
 

### Significance
A deficiency in SSADH function leads to abburant phenotypes of plants and even humans. Identification of more genetic targets that suppress ssadh phenotype has an important implication in the discovery of drugs against the disorder GHB acciduria, a disorder in humans caused by mutations in SSADH.


## Tools
Google colab, 
Googlesheets, 
Beekeper Studio,
SQLAlchemy to connect to the Postgress database,
SQL, 
Pands,
Seaborn,
Matplotlib,
Google slides


## Usage

To reproduce the code, run the googlecolab notebook file EMS_Analysis.ipynb file in the Github Notebook directory of the Genetic_Project. 


## Project Structure
- Data/: A directory containing the processed data of EMS mutagenesis. 
- Notebook/: A directory containing googlecolab notebook with an active code.
- Result/: .
- README.md/: A file containing an overview of the project.
## Data Analysis and Results

### Data
- The NGS data was generated as part of my PhD study in 2012. The raw data is not loaded on the Github. However, several extracts of the original data are loaded on Github. The partial genome sequence of chromosome 2 and 5 are downloaded from TAIR database. 
### Data Pre-processing
- Data type formats, unknown sequences, duplications are all cleaned using panda. 
- Merging of the NGS data and the genome sequence was done by using nucleotide position as a joining key.
## Analysis Results


## Visualization

## Screenshoots
https://drive.google.com/file/d/1na4HDIRQJ8Yz6wt2Lo0w3M2tNTLpZYOa/view?usp=sharing

## Authors

- [@derewor](https://github.com/derewor/TravelTide_Customer_Segmentation_projecte)

https://www.linkedin.com/in/dereje-worku-mekonnen-a8345217/




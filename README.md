# GWAS IN STORK Groruddalen (STORK G)

The QC procedure and variables used in STORK G have been described previously (https://doi.org/10.2217/epi-2022-0427, https://doi.org/10.1371/journal.pone.0256158 and https://doi.org/10.1093/hmg/ddac050). Hence, here is described briefly. 
 
# STORK G in brief 
 
STORK G is a population based cohort of 823 healthy women with different ancestries (European, South Asian, African, Middle Eastern and South American), attending three Child Health Clinics for antenatal care in Groruddalen, Oslo, Norway between 2008 and 2010. Women were eligible to participate if they: 1) Lived in the study districts; 2) planned to give birth at one of two study hospitals; 3) were <20 weeks pregnant; 4) could communicate in Norwegian or any of the translated languages; and 5) were able to give an informed consent. The STORK G study including genetic data is approved by the Norwegian Regional Committee for Medical Health Research Ethics South East (ref.number 2015/1035). We obtained written informed consent from all participants before any study-related procedure. The overall participation in STORK G was 74%.
 
# Genotyping QC
 
A total of 664 samples were genotyped using the Illumina CoreExome chip at Department of Clinical Sciences, Clinical Research Centre, Lund University, Malmö, Sweden. PLINK 1.9 software was used for QC variant filtering. Samples with low call rate (<95%, n=0), mismatched gender (n=24), cryptic relatedness (IBD > 0.185, n=6) and extreme heterozygosity (> |mean± (3xSD)|, n =1) were removed. 
Variants with call rate <95% (n=10081), MAF <1% (n=245221), and in deviation of Hardy Weinberg equilibrium (p<10e-06) were filtered. Approximately 300,000 were left for imputation and 438 women (300 European and 138 South Asian) passed the QC.
 
# Principal component (PC) generation
 
PCs were generated based on the variance-standardised relationship matrix method implemented in PLINK 1.9 [49].
 
# Imputation
 
Imputation was done separately for Europeans and South Asians by mapping the genome-wide association study scaffold to NBI build 37 of the human genome. Their correspondent 1000 genomes project panel was used (Phase 3, www.well.ox.ac.uk/~wrayner/tools/). IMPUTE2 software was used for imputation (version 2.3.2).
 
# Variables
 
In STORK G, Fasting glucose, 2-hour glucose and Hb1AC data were available at gestational week 28. All women underwent a 75g oral glucose tolerance test. Fasting and 2-hour glucose were obtained with a point of care instrument (HemoCue, Angelholm, Sweden). HbA1c levels in full blood were measured using HPLC (Tosoh G8). GDM diagnosis was determined per WHO 99 criteria (fasting glucose ≥ 7.0 mmol/l or 2-hour glucose ≥ 7.8 mmol/l). All the women were normoglycemic at inclusion (week 15).
 
# Analysis
 
All statistical analysis were done with SNPTEST (version 2.5.2). European and South Asian data were analysed separately. For all the GWAS performed, the dosages were analysed assuming an additive model and using the expected approach. The first 5 PCs were included as covariates.






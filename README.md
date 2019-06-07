# Subphenotyping with a topic modeling approach: non-negative matrix factorization (NMF) and EHR

This is the source code of paper

Using topic modeling via non-negative matrix factorization to identify relationships between genetic variants and disease phenotypes: A case study of Lipoprotein(a) (LPA)

**Accepted in PLOS ONE **

Manuscript at:https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0212112

The project explores the topic modeling via non-negative matrix factorization on structured Electronic health record data. The repository contains the relevant code to show the results in the paper. The abstract is provided below. The code can be implemented in related domain. 

The input data contains 12759 patients (samples) and 1853 unique phecodes. We used one-hot encoding to represent the data. Each row corresponds to a patient. The columns contains some demographic features, the 1853 unique phecode and one SNP column (named as Class in the data). To run the notebook, users might need to change the data to the above the format.

For privacy concern, we did not upload the raw dataset. We just provide the header of columns.

> *Abstract* 
Genome-wide and phenome-wide association studies are commonly used to identify important relationships between genetic variants and phenotypes. Most studies have treated diseases as independent variables and suffered from the burden of multiple adjustment due to the large number of genetic variants and disease phenotypes. In this study, we used topic modeling via non-negative matrix factorization (NMF) for identifying associations between disease phenotypes and genetic variants. Topic modeling is an unsupervised machine learning approach that can be used to learn patterns from electronic health record data. We chose the single nucleotide polymorphism (SNP) rs10455872 in LPA as the predictor since it has been shown to be associated with increased risk of hyperlipidemia and cardiovascular diseases (CVD). Using data of 12,759 individuals with electronic health records (EHR) and linked DNA samples at Vanderbilt University Medical Center, we trained a topic model using NMF from 1,853 distinct phenotypes and identified six topics. We tested their associations with rs10455872 in LPA. Topics enriched for CVD and hyperlipidemia had positive correlations with rs10455872 (P < 0.001), replicating a previous finding. We also identified a negative correlation between LPA and a topic enriched for lung cancer (P < 0.001) which was not previously identified via phenome-wide scanning. We were able to replicate the top finding in a separate dataset. Our results demonstrate the applicability of topic modeling in exploring the relationship between genetic variants and clinical diseases.


## Note
Please note, if you need to use the code for any kind of academy use or commecial use, please cite paper:
Zhao J Feng Q, Wu P, Warner JL, Denny JC, Wei W-Q. Using topic modeling via non-negative matrix factorization to identify relationships between genetic variants and disease phenotypes: A case study of Lipoprotein (a)(LPA). PloS one. 2019; 14(2) doi.org/10.1371 



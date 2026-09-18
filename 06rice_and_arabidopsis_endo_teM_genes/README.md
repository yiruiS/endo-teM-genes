# Identifying Imprinted Genes in Rice and Arabidopsis

## identify rice endosperm teM genes
>Input files:
>>1. Rice expression data from multiple tissues  
>>2. Rice methylation data from leaf

>Criterion:
>>1. 10 CHG and ≥ 40% CG and CHG in the CDS reginos
>>2. ≥ 5-fold increase in TPM in endosperm compared to other sporophyte tissues
>>3. genes has no less than 20TPM in edosperm

## rice imprinting information
>The rice MEGs and PEGs gene lists were downloaded from Tonosaki, K., Susaki, D., Morinaka, H. et al. Multilayered epigenetic control of persistent and stage-specific imprinted genes in rice endosperm. Nat. Plants 10, 1231–1245 (2024). https://doi.org/10.1038/s41477-024-01754-4

## identify arabidopsis endosperm teM genes
>Input files:
>Arabidopsis seed single cell RNA-seq
>Arabidopsis bulk RNA-seq from multiple tissues
>Arabidopsis methylation data from leaf

>Criterion:
>>1. 10 CHG, ≥ 40% CG, and ≥ 20%CHG in the CDS reginos
>>2. ≥ 5-fold increase in TPM in endosperm compared to other sporophyte tissues
>>3. genes has no less than 20TPM in edosperm

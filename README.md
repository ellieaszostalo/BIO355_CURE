Scripts created for analyses of inbreeding and genomic erosion in Great Gray Owl populations in the northwestern United States

Project HackMD: https://hackmd.io/@ellieszostalo/r1MM4c_sWe

Reason for lack of scripts prior to FST + ROH:
There are not script pipelines for calculating heterozygosity and SNPs as these were run before learning script creation. The code that was run is explained in project HackMD

# BIO355 CURE Project – Inbreeding and Genomic Erosion in Great Gray Owls

## Dataset

-   Source (DOI / link): https://doi.org/10.1007/s10592-020-01280-8
-   Species/system: Great Gray Owl (Strix nebulosa)
-   Data type: VCF

------------------------------------------------------------------------

## Research questions

1.  Can we identify ROH to uncover inbreeding and potential signals of genomic erosion/inbreeding?

2.  What is the extent of variation in genomic erosion/loss of genetic diversity between different sample locations?
Hypothesis 1: populations that are more genetically isolated will display higher levels of genomic erosion due to obstructed gene flow as a result of no connecting habitats (Mendelsohn et al., 2017). Based on this knowledge, we hypothesize that populations with higher levels of genetic differentiation will display higher genomic erosion, while populations with more connectivity will preserve a higher rate of genetic diversity. 
Hypothesis 2: If the observed genetic differentiation is a result of historical isolation 
rather than recent mating between close relatives in the population, we will likely see high population differentiation but not encounter a significant presence of runs of homozygosity.

3.  Using location as an identifier, what are the conservation implications of inbreeding in subpopulations?
The most likely biological process behind inbreeding and genomic erosion in the Great Gray Owl populations is isolation because of geographic obstruction (Mendelsohn et al., 2017). 

------------------------------------------------------------------------

## Analyses

-   FST (pairwise comparison)
-   ROH / inbreeding 
-   Population and Species Level Heterozygosity and Homozygosity

------------------------------------------------------------------------

## Folder structure

-   `data_raw/` → original downloaded data\
-   `data_processed/` → filtered/modified data\
-   `metadata/` → sample lists, population assignments\
-   `scripts/` → analysis scripts\
-   `results/` → output files\
-   `figures/` → final figures

------------------------------------------------------------------------

## Workflow notes

Brief summary of your workflow: 
- How data was filtered 
- Key analysis steps 
- Any important decisions

------------------------------------------------------------------------

## Notes

-   Any challenges or important observations of the data

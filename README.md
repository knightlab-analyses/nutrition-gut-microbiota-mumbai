# Analysis artifacts: _Nutrition and the gut microbiota in 10–18-month-old children living in urban slums of Mumbai, India._

**Codebook:** `"Microbiome Data Dictionary - QIIME 2.xlsx"`

## Folders

- **`diversity`:** Contains diversity-related inputs/outputs used in this analysis.
- **`diversity/deicode`:** Contains DEICODE ([Martino et al. 2019](https://msystems.asm.org/content/4/1/e00016-19.abstract))-related inputs and outputs.
- **`diversity/qurro`:** Contains Qurro ([Fedarko et al. 2020](https://academic.oup.com/nargab/article/2/2/lqaa023/5826153))-related inputs and outputs.
- **`diversity/unifrac-permanova`:** Contains Unweighted/Weighted UniFrac (as
  tested by PERMANOVA) outputs.
- **`diversity/unifrac-permdisp`:** Contains Unweighted/Weighted UniFrac (as
  tested by PERMDISP) outputs.

## What is this repository?

This repository includes all of the QIIME 2 (2019.7) outputs and program related to this study, _Nutrition and the gut microbiota among 10–18-month-old children living in urban slums of Mumbai, India_ (1), an ancillary study from a larger randomized controlled trial (2, 3). The objectives of this study are detailed in the Abstract: In this cross-sectional study, we describe the composition and diversity of the gut microbiota among undernourished children living in urban slums of Mumbai, and determine how nutritional status, including anthropometric measurements, dietary intakes from complementary foods, feeding practices, and micronutrient concentrations, are associated with their gut microbiota, for the first time. We collected rectal swabs from children aged 10–18 months living in urban slums of Mumbai participating in a randomized controlled feeding trial and conducted 16S rRNA sequencing to determine the composition of the gut microbiota. Across the study cohort, Proteobacteria dominated the gut microbiota at over 80% relative abundance, with Actinobacteria representation at <4%, suggesting immaturity of the gut. Increased microbial &alpha;-diversity was associated with current breastfeeding, greater head circumference, higher fat intake, and lower hemoglobin concentration and weight-for-length Z-score. In redundancy analyses, 47% of the variation in Faith's PD could be accounted for by age, and iron and polyunsaturated fatty acid intakes. Differences in community structure (&beta;-diversity) of the microbiota were observed among those consuming fats and oils the previous day compared to those consuming none. Our findings suggest that growth, diet, and feeding practices are associated with gut microbiota metrics in undernourished children, whose gut microbiota were comprised mainly of Proteobacteria, a phylum containing many potentially pathogenic taxa.

Full processing code may be found in the file "Mumbai Full Processing Code.txt". The steps used mainly follow the [Moving Pictures Tutorial](https://docs.qiime2.org/2019.7/tutorials/moving-pictures/) with some exceptions (using the fragment insertion method, DEICODE, Qurro, etc).

## Data availability
These data were subject to cross-checking and confirmation by the Cornell Institute for Social and Economic Research (CISER) (member of DataCite, https://doi.org/10.5281/zenodo.556235) to ensure reproducibility; datasets and code are available at https://doi.org/10.6077/zrvc-pc31. The data that support the findings of this study are openly available in NCBI BioProject at http://doi.org/[doi], reference number PRJNA657036. The DNA sequences corresponding to the 16S rRNA gene data in this study have been submitted as raw fastq files to the SRA at https://www.ncbi.nlm.nih.gov/sra/PRJNA657036.

## References

(1) Huey SL, Jiang L, Fedarko M, McDonald D, Martino C, Ali F, Russell DG, Udipi SA, Thorat AT, Thakker V, Ghugre P, Potdar RD, Chopra H, Rajagopalan K, Haas JD, Finkelstein JL, Knight R, Mehta S. "Nutrition and the gut microbiota among 10–18-month-old children living in urban slums of Mumbai, India."
(2) https://clinicaltrials.gov/ct2/show/NCT02233764
(3) Mehta, S., Finkelstein, J. L., Venkatramanan, S., Huey, S. L., Udipi, S. A., Ghugre, P., ...  Haas, J. D. (2017). "Effect of iron and zinc-biofortified pearl millet consumption on growth and immune competence in children aged 12–18 months in India: study protocol for a randomised controlled trial." _BMJ Open, 7_(11), e017631. https://doi.org/10.1136/bmjopen-2017-017631


Code files available upon request. Contact: Samantha L. Huey, slh277@cornell.edu.

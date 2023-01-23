[![License: CC BY-NC-ND 4.0](https://img.shields.io/badge/License-CC_BY--NC--ND_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-nd/4.0/)

## Repository for the figures and supplementary for PhD thesis

----

### Citation:

> Zhang H. 2023. Genomic studies of sex differences: On mutations, recombination, and sexual antagonism in songbirds. Lund: Lund University (Media-Tryck). 226 p.

Links to the thesis:

----

### List of figures

#### Kappa

Figure|Link|Description
:----|:-|:--------------------
__Figure 1__ | [Link](https://github.com/HKyleZhang/Thesis_Figure_and_Supplementary/blob/main/0.Kappa/Figure/Figure_01.png) | Sexual dimorphism quantified as the male-to-female difference in plumage colouration scores among selected species in Sylvioidea, Muscicapoidea, and Passeroidea superfamilies. Illustrations show monochromatic (_e.g._, great reed warbler, _A. arundinaceus_), and dichromatic (_e.g._, Spanish sparrow, _P. hispaniolensis_), males and females of some species. Birds illustrations were from the Handbook of the Birds of the World (del Hoyo and Elliott, 2006).
__Figure 2__ | [Link](https://github.com/HKyleZhang/Thesis_Figure_and_Supplementary/blob/main/0.Kappa/Figure/Figure_02.png) | Illustration of different stages in the evolution of sexual antagonism. (A) A sexually monomorphic trait with different fitness optima in males and females, resulting in sexually antagonistic selection that is quantified by the opposing slopes of the relationships between relative fitness and phenotype across individual females and males. (B) Sexual dimorphism evolves as male and female phenotypic distributions move toward their respective fitness optima in response to sexually antagonistic selection. (C) A hypothetical endpoint in which the phenotypic distributions of males and females match their fitness optima, and sexual antagonism is resolved at the loci for this trait. This figure was adaptated from Cox (2017).
__Figure 3__ | [Link](https://github.com/HKyleZhang/Thesis_Figure_and_Supplementary/blob/main/0.Kappa/Figure/Figure_03.png) | (A) The number of DNMs of paternal origin is plotted against the father’s age (in years). The blue line shows the linear fit (estimate of the slope=0.31, p=5.15 × 10−4) and the grey band represents the 95% confidence interval. (B) The number of DNMs of maternal origin is plotted against the mother’s age (in years), the blue line shows the linear fit (estimate of slope=0.12, p=0.02), and the grey band represents the 95% confidence interval. The figure was adapted from Wong _et al._ (2016).
__Figure 4__ | [Link](https://github.com/HKyleZhang/Thesis_Figure_and_Supplementary/blob/main/0.Kappa/Figure/Figure_04.png) | Examples of sex differences in recombination landscapes. Local recombination rates are greater in males at chromosome ends, while local rates are often greater in females near the centromere (shown by the green bars). (A) Recombination along human chromosome 7 (Broman _et al._, 1998). (B) Recombination along domestic dog chromosome 19 (Wong _et al._, 2010). (C) Distribution of crossovers as function of relative distance from centromere across long arms of all Gasterosteus stickleback chromosomes (Sardell _et al._, 2018). The figure was adapted from Sardell and Kirkpatrick (2020).
__Figure 5__ | [Link](https://github.com/HKyleZhang/Thesis_Figure_and_Supplementary/blob/main/0.Kappa/Figure/Figure_05.png) | Distribution range of great reed warbler in summer (orange) and winter (blue). The map and bird illustration were from the Handbook of the Birds of the World (del Hoyo and Elliott, 2006).
__Figure 6__ | [Link](https://github.com/HKyleZhang/Thesis_Figure_and_Supplementary/blob/main/0.Kappa/Figure/Figure_06.png) | Phylogeny of the 13 selected species.
__Figure 7__ | [Link](https://github.com/HKyleZhang/Thesis_Figure_and_Supplementary/blob/main/0.Kappa/Figure/Figure_07.png) | The three-generation pedigree of great reed warblers (_Acrocephalus arundinaceus_). Shown are generation (F0, F1, and F2), individual code (_e.g._, H7-38) and sex (square: male; circle: female).
__Figure 8__ | [Link](https://github.com/HKyleZhang/Thesis_Figure_and_Supplementary/blob/main/0.Kappa/Figure/Figure_08.png) |Two scenarios of the occurrence and fate of germline mutations in a three-generation pedigree. (A) The first scenario involves germline mutations occurring in one individual (_e.g._, H7-38) of F0 generation, detected in one individual (_e.g._, H3-00) of F1 generation, and then present in several individuals (e.g., 254, 256, 257) of F2 generations. (B) The second scenario involves the germline mutations occurring in one individual (_e.g._, H3-00) of F1 generation and detected in one individual (e.g., 257) of F2 generation.
__Figure 9__ | [Link](https://github.com/HKyleZhang/Thesis_Figure_and_Supplementary/blob/main/0.Kappa/Figure/Figure_09.png) | The workflow of using RecView. Solid lines indicate the basic workflow while dashed lines indicate the optional workflow. RecView requires an input genotype file which can be generated by using _make_012gt()_ on the output file from VCFtools, or using _make_012gt_from_vcf()_ on the VCF file. _RecView_ further requires an input scaffold file containing the order and orientation of the scaffolds. These two input files are used together with the built-in dictionary of grandparent-of-origin (GoO) to produce the GoO figure showing the GoO inferences of alleles along the scaffolds, and a figure showing the informative alleles density. RecView can further locate putative recombination positions with the proportional difference or cumulative continuity score algorithms and output result figures and tables. The result figures and tables can be saved, including an intermediate table containing the GoO inferences at each SNP.
__Figure 10__ | [Link](https://github.com/HKyleZhang/Thesis_Figure_and_Supplementary/blob/main/0.Kappa/Figure/Figure_10.png) | Examples of the occurrence and inheritance of crossover in individuals of F1 generation. The locations of recombination are visualised as the boundaries of two chromosome regions with different colours in individuals of F2 generation. Different colours indicate different grandparent-of-origins (_i.e._, individuals of F0 generation).
__Figure 11__ | [Link](https://github.com/HKyleZhang/Thesis_Figure_and_Supplementary/blob/main/0.Kappa/Figure/Figure_11.png) | Estimates of tRC across 51 neo-sex chromosome genes from (A) the dS approach, (B) the MLCT approach, (C) the ELW approach, and (D) the BEAST approach. Genes were ordered according to the physical positions on great reed warbler’s neo-Z, and included 22 genes from the ancestral part and 29 genes on the added part (Sigeman _et al._, 2021). Colours correspond to clusters of a K-means clustering analysis (k = 2), with brown indicating Cluster 1 and blue Cluster 2. The colour gradient (heatmap) in the ELW approach indicates the ELW values for each hypothetical topology. The two horizontal lines mark the origin of Neognathae (green) and Sylvioidea (red).
__Figure 12__ | [Link](https://github.com/HKyleZhang/Thesis_Figure_and_Supplementary/blob/main/0.Kappa/Figure/Figure_12.png) |Parent-of-origin for the DNMs.
__Figure 13__ | [Link](https://github.com/HKyleZhang/Thesis_Figure_and_Supplementary/blob/main/0.Kappa/Figure/Figure_13.png) | The GUI of RecView with the setting panel (red square) for uploading input files (yellow square) and setting options and the output panel (green square) where results can be accessed by selecting different tabs (orange square).
__Figure 14__ | [Link](https://github.com/HKyleZhang/Thesis_Figure_and_Supplementary/blob/main/0.Kappa/Figure/Figure_14.png) | The grandparental-of-origin of informative alleles at all SNPs along chromosome 1 in great reed warbler offspring ID-256 for. Dots are plotted with noise on the y-axis to alleviate the degree of overlap. Colouration indicates different scaffolds on chromosome 1 in the great reed warbler genome assembly (Sigeman _et al._, 2021).
__Figure 15__ | [Link](https://github.com/HKyleZhang/Thesis_Figure_and_Supplementary/blob/main/0.Kappa/Figure/Figure_15.png) | CO rates and locations between sexes. (A) Recombination rates were not significantly different between males and females. (B) Physical distance and (C) proportional distance of COs from the telomeric end of chromosome arms were significantly different, with more COs near the telomeric end in males than females. 
__Figure 16__ | [Link](https://github.com/HKyleZhang/Thesis_Figure_and_Supplementary/blob/main/0.Kappa/Figure/Figure_16.png) | Pairwise linkage disequilibrium squared correlations (r2) between the SNPs within 100 kb. The scale at the bottom (black) indicates the physical distance (bp) between the SNPs. The scale at the top (red) indicates the distribution of the data points within the 100 kb. The scale on the right (red) indicates the distribution of the data points between 0.00 – 1.00 of r2.
__Figure 17__ | [Link](https://github.com/HKyleZhang/Thesis_Figure_and_Supplementary/blob/main/0.Kappa/Figure/Figure_17.jpg) | FST values (A) and weighted mean FST values in a 10-kb window (B) on different chromosomes. Solid red line delimits the top 10 and dashed red line delimits the top 100 SNPs or windows with highest mean FST. “Unplaced” groups the data points on the scaffolds that were not assigned to chromosomes.
__Figure 18__ | [Link](https://github.com/HKyleZhang/Thesis_Figure_and_Supplementary/blob/main/0.Kappa/Figure/Figure_18.jpg) | Significance values of single SNPs along the different chromosomes from a GWAS analysis with sex. Solid red line delimits the top 10 most significant SNPs and dashed red line delimits the top 100 most significant SNPs. “Unplaced” groups the data points on the scaffolds that were not assigned to chromosomes.
__Figure 19__ | [Link](https://github.com/HKyleZhang/Thesis_Figure_and_Supplementary/blob/main/0.Kappa/Figure/Figure_19.png) | Comparing FST and significance of association with sex from GWAS for the top 100 SNPs in respective analyses, with the SNPs exclusively identified in FST-based approach (yellow), exclusively identified in GWAS approach (brown), the SNPs identified in both FST-based and GWAS approaches (red).

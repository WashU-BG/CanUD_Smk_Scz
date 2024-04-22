## Phenotype description
We performed a cross-disorder analysis using summary statistics from the largest available GWAS of each trait: Scz, CanUD and tobacco smoking:
 
**Schizophrenia (Scz)**: We used data from the most recent Psychiatric Genomics Consortium (PGC) Schizophrenia genome-wide association study (GWAS) meta-analysis of individuals of European ancestry (N = 161,405; Ncases = 67,390)32. We also analyzed summary statistics from a GWAS meta-analysis of schizophrenia in African ancestry individuals (N = 15,846; Ncases = 7509), from the Cooperative Studies Program (CSP) #572 and the Genomic Psychiatry Cohort35.

**Cannabis use disorder (CanUD)**: We used data from Levey et al.’s recent GWAS meta-analysis of cannabis use disorder17, which combined data from the Million Veteran Program (MVP), the PGC, the Lundbeck Foundation Initiative for Integrative Psychiatric Research, and deCODE Genetics (European ancestry N = 886,025; Ncases = 42,281; African ancestry N = 120,208; Ncases = 19,065).

**Ever-smoked tobacco regularly (Smk)**: We used summary statistics from the GWAS & Sequencing Consortium of Alcohol and Nicotine use (GSCAN) GWAS of self-reported ever/never regular cigarette smoking (European ancestry N = 805,431; Never = 393,707; African ancestry N = 24,278; Ncases = 9,916)36. We used the publicly-available set of summary statistics, which does not include data from 23andMe; the sample sizes reported here reflect that exclusion. 

We used ‘Association analysis based on SubSETs’ (ASSET; Bhattacharjee, S. *et al.*, 2012) to combine the GWAS summary data for CanUD, Smk and Scz (separately by ancestry), using the two-tailed meta-analysis approach to obtain a single cross-disorder association statistic. Unlike traditional meta-analysis approaches, ASSET takes into account SNPs with significant effects on multiple disorders even if the effects on the traits are in opposite directions. We used the LDSC genetic covariance intercept to approximate the degree of sample overlap amongst the studies and included it in the ASSET covariance matrix. Default parameters were applied using the ‘h.traits’ function.

We provide the summary statistics in their direct output format from ASSET, but these can be separated into subsets if desired. In our manuscript, we use the following notation for each subset: ∩ represents variant subsets with the same directions of effect (+ or -), and | represents variant subsets whose effect sizes are in the opposite direction of those for one versus the other two traits. We defined four subsets: (1) Scz ∩ CanUD ∩ Smk (i.e., a subset with convergent effects across all 3 traits); (2) Scz ∩ CanUD | Smk (i.e., a subset of variants with convergent effects for Scz and CanUD, but divergent effects for Smk); (3) Scz ∩ Smk | CanUD; and (4) CanUD ∩ Smk | Scz.


## Download Instructions
Summary statistics are available to download via box using the link below:


## Citation for studies using this data

[will be updated with reference once published]

## File description

| Column | Description |
| --- | --- |
| CHR | chromosome |
| POS | genome position |
| rsid | rs ID for variant |
| Allele1 | allele 1 |
| Allele2 | allele 2 |
| N | sample size |
| BETA | effect size of allele 1 |
| SE | standard error of BETA |
| p.value | p value |

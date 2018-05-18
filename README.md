## README
This is the repository for final project from the course *Introducción a la bioinformática e investigación reproducible para análisis genéticos* created by Julia Carrasco Zanini Sánchez. It contains 4 directories:
- `Meta`: contains the AIMs' raw data reported as the base sequenced for every allele of all patients included in the study.
- `Data`: contains data bases that can be read into `R` for principal component analysis and for association analysis between the genetic variants and serum levels of different metabolites.
- `Bin`: contains 3 scripts.
	- The first script is written in bash and calls `PLINK` software to recode the Ancetry Informative Markers' allele data into additive model (0,1 or 2 risk alleles).
	- The second script is written in `R` and reads the output from `PLINK`'s `recodeAD` command and conducts principal component analysis for the AIMs.
	- The thrid script is written in `R` and reads the data base containing one carbon metabolism SNPs and serum glucose, homocysteine, folate and vitamin B12 levels. 

- `Figures`: contains figures' files and rendered code used to generate the figures. 
# Like mother, like daughter? Phenotypic plasticity, environmental covariation, and heritability of size in a parthenogenetic wasp 

*Authors:* Alicia Tovar, Scott Monahan, Trevor Mugoya, Adrian Kristan, Walker Welch, Ryan, Dettmers, Camila Arce, Theresa Buck, Michele Ruben, Alexander Rothenberg, Roxane Saisho, Ryan Cartmill, Timothy Skaggs, Robert Reyes, MJ Lee, John Obrycki, William Kristan, Arun Sethuraman.

Find our [preprint!](https://www.biorxiv.org/content/10.1101/2022.12.02.518902v3)

## Preliminary Setup.
The repository contains the requisite morphological data in the `DATA/` directory and analysis scripts are present in their own respective dirtectories;

1. Clone Repository
```bash
git clone https://github.com/ChabbyTMD/D_coccinellae_Paper.git
```
2. Set Working Path

At the beginning of each analysis R script in the `Libraries` subsection, set the relative or absolute path to the `morph_data_bk.xlsx` file from the `DATA` directory.

## Statistical Analysis and Figure Directories

1. Parent Offspring Regressions ([Linear_Regression](Linear_Regression/wasp_lm.Rmd))
2. Redundancy Analysis ([RDA](RDA/Final_RDA_Analysis.Rmd))
3. Paper Figures ([Figures](Figures/Figures.Rmd))
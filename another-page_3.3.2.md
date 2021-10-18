## What's New?

GAIA v3.3.2

* gaia-shiny

Added gnomAD r3.1.1 genomes in the filtering logic. 

The logic is 

(gnomAD r2.1.1 exomes + gnomAD r3.1.1 genomes) below user selected threshold. Default standard is 1/1000 for de novo and XL and 1/50 for AR. 

(gnomAD r2.1.1 exomes hom_alt + gnomAD r3.1.1 genomes hom_alt) below user selected threshold. Default standard is 3 counts. 

If NULL value, regard as zero. 

[back](./)

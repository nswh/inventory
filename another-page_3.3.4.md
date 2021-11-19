## What's New?

GAIA v3.3.4

* gaia-cromwell

Updated OMIM to 20211116

Update Mastermind to 2021.10.12

Update ClinVar to 2021.11.13

* gaia-shiny

Fix the bug of calculating gnomAD AF: (AF_exome * samplesize_exome + AF_genome * samplesize_genome ) / totalsamplesize. Refer to https://gnomad.broadinstitute.org/downloads The SQL Syntex is: 
```
paste("(CAST(gnomad_af as decimal) * 251496 + CAST(gnomad_genomes_af as decimal) * 152312) / 403808 <= %s AND ",
           "(CAST(gnomad_afr_af as decimal) * 251496 + CAST(gnomad_genomes_afr_af as decimal) * 152312) / 403808 <= %s AND ",
           "(CAST(gnomad_genomes_ami_af as decimal) <= %s OR gnomad_genomes_ami_af IS NULL) AND ",
           "(CAST(gnomad_amr_af as decimal) * 251496 + CAST(gnomad_genomes_amr_af as decimal) * 152312) / 403808 <= %s AND ",
           "(CAST(gnomad_asj_af as decimal) * 251496 + CAST(gnomad_genomes_asj_af as decimal) * 152312) / 403808 <= %s AND ",
           "(CAST(gnomad_eas_af as decimal) * 251496 + CAST(gnomad_genomes_eas_af as decimal) * 152312) / 403808 <= %s AND ",
           "(CAST(gnomad_fin_af as decimal) * 251496 + CAST(gnomad_genomes_fin_af as decimal) * 152312) / 403808 <= %s AND ",
           "(CAST(gnomad_genomes_mid_af as decimal) <= %s OR gnomad_genomes_mid_af IS NULL) AND ",
           "(CAST(gnomad_nfe_af as decimal) * 251496 + CAST(gnomad_genomes_nfe_af as decimal) * 152312) / 403808 <= %s AND ",
           "(CAST(gnomad_oth_af as decimal) <= %s OR gnomad_oth_af IS NULL) AND ",
           "(CAST(gnomad_sas_af as decimal) * 251496 + CAST(gnomad_genomes_sas_af as decimal) * 152312) / 403808 <= %s", sep = ""))
```

Internal Allele Frequency Control Cohort expanded from 199 to 393, where a subset of 102 Mendelion Samples (49 Female, 53 Male) were chosen as CNV baseline.	

Fix the sliding bar notation for gnomAD genome filter. 

[back](./)

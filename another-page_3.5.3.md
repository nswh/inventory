## What's New?

GAIA v3.5.3 (release date 20240723)

### * gaia-cromwell

Show full legend in Ancestry Estimate html file.  `20240808`

HGMD upgrade to 2024 Q2  `20240729`

Delete the date specified cromwell configure file which uses S3.  `20240729`

Seperate cromwell configure file to S3 specific. `20240729`

----------------------------------------------------------------------------------------------------------------------------------------

upgrade ClinVar to 20240630, OMIM to 20240707  `20240708`

Versioning tag from 3.5.2 to 3.5.3  `20240705`

Perform Ancestry Estimate for each family.  `20240702`

### * gaia-init-ref-files

HGMD VCF header 2024.2 `20240729`

HGMD updated to 2024 Q2  `20240729`

----------------------------------------------------------------------------------------------------------------------------------------

upgrade OMIM to 20240707  `20240708`

upgrade ClinVar to 20240630  `20240707`

### * gaia-shiny

Adding http_keepalive_timeout 600; to the top level in the shiny-server.conf file solved the timeout issue for QC metrics R markdown file generation.  `20240910`

Fix the QC metrics download issue. kable matrix too long.  `20240903`

Due to environment change in GAIA frontend. The command docker rmi -f dollar(docker images -a -q) FORCE removed some dependencies of previous gemini installation, which cause miniconda solve environment forever. There are some functions in Batches does not work. So rebuild 3.5.3 after rocker/shiny 4.4.1 by copying gemini from gaia-shiny:3.0.0 without installation.  `20240901`

Remove warning messages in R markdown html QC metrics report  `20240815`

Display and download Somalier Ancestry Estimation result  `20240815`

Expand the browser window to display all batch analysis samples, capacity is 6*9=54. The maximum on the plate is 96/2=48.  `20240806`

remove gene MCOLN1 from CNV query.Add QC metrics in batch analysis output.  `20240801`

----------------------------------------------------------------------------------------------------------------------------------------

remove Ashkenazi varaints from Cystic_Fibrosis_CFTR.bed as requested by Nila  `20240715`

Add batch analysis for TWIST panelV2, CFTR only.The GAIA enquiry code is pre-executed, not on the spot SQL enquiry.  `20240709`

RPRM GAIA enquiry BED region UTR5 expand 60 bases, UTR3 expand 10 bases.  `20240709`

Add ancestry estimate result for each family.  `20240709`

### For a detailed referece resource data please see either QC Metrics Report HTML file from analysis portal or [GAIA version](./another-page_3.5.3_GAIA_version.html)

[back](./)

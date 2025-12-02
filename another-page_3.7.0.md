## What's New?

GAIA v3.7.0 (release date TBA)

### * gaia-annotate

Upgrade VEP version from 110 to 115 for gnomAD v4.1.  `20251125`

### * gaia-shiny

Fix to display number of hom_alt count for autosome chromosome. Display gnomAD URL regardless of existence in db.  `20251202`

Change gnomad_dominant filter for RCS from 0.002% to 0.02%  `20251126`

Enable batches analysis by default select a database.	`20251122`

categorize Illumina SpliceAI to NoScore, LowScore and >=0.2	`20251122`

Add PanelApp in Batches analysis, etc.	`20251119`

Don't display GOTO_gnomAD if there is no variant.	`20251110`

Display AC_XY as number of hemi alongside of nhomalt.	`20251109`

gnomad_dominant filters only land on 0.002% for rare disease, 0.02% for common disease, 2% for batch,no_model and 100%.	`20251030`

Revert query_gemini_batch.R to original status	`20251027`

gnomad_dominant slide bar land only on 0.002% for rare disease, 0.02% for common/adult disease and 100% for no model	`20251027`

Update Reproductive_Carrier_Screening gene list	`20251023`

Add Paradoxical X-linked (dominant filtering) for couple analysis	`20251023`

Update gene symbol query to match VEP115 bed	`20251023`

Add MutScore column.	`20251010`

LIRICAL using exomiser 2502_hg38	`20251010`

Add MIZTLI and PanelApp content, include Imprinted Genes.	`20251009`

Add explanation in PLINK Sex estimate of the F-value.	`20251009`

Fix the problem of when searching CNV by gene symbol, no downloadable sheet, incorrect warning message.	`20251009`

Add common CNV track.	`20251006`

Add Alamut URL, jMorp URL, Our DNA URL and MaveDB accession number.	`20251006`

Resolve the issue of pop up checking filters box not respoding problem.	`20251006`

Upgrade dbNSFP to 5.2a	`20251006`

Upgrade gnomAD to 4.1 joint exome and genome	`20251006`

Upgrade rocker-shiny to 4.5.1	`20251006`

Upgrade LIRICAL to 2.2.0	`20251006`

### * gaia-init-ref-files

CNV baseline upgrade for WES, panel and WGS	`20251127`

Upgrade VEP 110-115 for HGNC gene symbol nomenclature.	`20251127`

Upgrade CNV annotation only.	`20251127`

Upgrade VEP 110-115	`20251127`

Remove VEP 103-110 log	`20251127`

Remove previous VEP 97-103-110 updates associated HGNC gene symbol nomenclature.	`20251127`

### * gaia-cromwell

Change input and output to align with VEP 115  `20251127`

Upgrade VEP 110-115  `20251127`

### * pow-gaia-brain

many things of workflow change

### For a detailed referece resource data please see either QC Metrics Report HTML file from analysis portal or [GAIA version](./another-page_3.7.0_GAIA_version.html)

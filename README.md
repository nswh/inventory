## NSWHP Genomic Annotation Interpretation Application (GAIA) and GenPhen Atlas Inventory List

### [GenPhen Atlas](http://192.168.106.139:8000/)

*  For trial only, include ~5000 samples sequenced on NovaSeq6000 from 2020 to early 2022

### [AmpMap v1.1.0 - for Long-read Amplicon Sequencing Reports](http://192.168.106.139:5001/)

### [Long Read WGS - sample inventory](http://192.168.106.136:5001/)

### GAIA 3.7.1 - for NovaSeq GRCh38/hg38 (release date 20260313) [What's New](./another-page_3.7.1.html)?

[LAB PRODUCTION - Genomics Annotation Interpretation Analysis pipeline (GAIA 3.7.1)](http://192.168.106.151:5883/)

[LAB BACKUP - Genomics Annotation Interpretation Analysis pipeline (GAIA 3.7.1)](http://192.168.106.139:5883/)

[CLOUD DEVELOPMENT - Genomics Annotation Interpretation Analysis pipeline (GAIA 3.7.1)](http://pilot.gaia.nswhp.com.au:5883/)

For databases: 
*     PTW_25_0915C_V2, PTW_25_1006B_V2 and PTW_26_0302A onwards
*     re-analysis (only runs after POWH_21-566, include POWH_21-566 will have CNV result. Check OMNI for run number. )
*     WGS from AGRF once validated

### GAIA 3.7.0 - for NovaSeq GRCh38/hg38 (release date 20251211) [What's New](./another-page_3.7.0.html)?

[LAB PRODUCTION - Genomics Annotation Interpretation Analysis pipeline (GAIA 3.7.0)](http://192.168.106.151:5882/)

[CLOUD DEVELOPMENT - Genomics Annotation Interpretation Analysis pipeline (GAIA 3.7.0)](http://pilot.gaia.nswhp.com.au:5882/)

For databases: 
*     PTW_25_1117B onwards, officially PTW_25_1208A onwards
*     re-analysis (only runs after POWH_21-566, include POWH_21-566 will have CNV result. Check OMNI for run number. )
*     WGS RGS_PRI15800 for re-analysis

### GAIA 3.6.3 - for NovaSeq GRCh38/hg38 (release date 20250605) [What's New](./another-page_3.6.3.html)?

[LAB PRODUCTION - Genomics Annotation Interpretation Analysis pipeline (GAIA 3.6.3)](http://192.168.106.151:5881/)

[CLOUD DEVELOPMENT - Genomics Annotation Interpretation Analysis pipeline (GAIA 3.6.3)](http://pilot.gaia.nswhp.com.au:5881/)

For databases: 
*     PTW_25_0526A onwards
*     re-analysis (only runs after POWH_21-566, include POWH_21-566 will have CNV result. Check OMNI for run number. )
*     WGS RGS_PRI15467 onwards

| Run | GAIA | DRAGEN | TWISTexome/MSOS version | reference genome |
|-----|------|--------|-------------------------|------------------|
| PTW_25_1117B | 3.7.0 and 3.6.3 | 3.10.4 | V1 | hg38noHLA |
| PTW_25_1124A | 3.7.0 and 3.6.3 | 3.10.4 | V1 | |
| PTW_25_1201A | 3.7.0 and 3.6.3 | 3.10.4 | V1 | |
| PTW_25_1201B | 3.7.0 and 3.6.3 | 3.10.4 | V1 | |
| PTW_25_1208A | 3.7.0 only | 4.3.6001 | V1 | 1KGhg38v4 |
| PTW_25_1215A | 3.7.0 only | 4.3.6001 | V1 | |
| PTW_25_1222A_02 | 3.7.0 only | 4.3.6001 | V1 | |
| PTW_25_1229A | 3.7.0 only | 4.3.6001 | V1 | |
| PTW_26_0105A | 3.7.0 only | 4.3.6001 | V1 | |
| PTW_26_0105B | 3.7.0 only | 4.3.6001 | V1 | |
| PTW_26_0112A_2 | 3.7.0 only | 4.3.6001 | V1 | |
| PTW_26_0119A | 3.7.0 only | 4.3.6001_noML for exome, 4.3.6001 for panel | V1 | |
| PTW_26_0126A | 3.7.0 only | 4.3.6001_noML for exome, 4.3.6001 for panel | V1 | |
| PTW_26_0202A | 3.7.0 only | 4.3.6001_noML for exome, 4.3.6001 for panel | V1 | |
| … | 3.7.0 only | 4.3.6001_noML for exome, 4.3.6001 for panel | V1 | |
| PTW_26_0223A | 3.7.0 only | 4.3.6001_noML for exome, 4.3.6001 for panel | V1 | |
| PTW_26_0302A | 3.7.1 only | 4.3.6001_noML for exome, 4.3.6001 for panel | V2 | |
| PTW_26_0309B | 3.7.1 only | 4.3.6001_noML for exome, 4.3.6001 for panel | V2 | |
| PTW_26_0309A | 3.7.1 only | 4.3.6001_noML for exome, 4.3.6001 for panel | V2 | |
| PTW_26_0316A | 3.7.1 only | 4.3.6001_noML for exome, 4.3.6001 for panel | V2 | |
| PTW_26_0316B_02 | 3.7.0 only | 4.3.6001_noML for exome, 4.3.6001 for panel | V1 | |
| … | 3.7.1 only | 4.3.6001_noML for exome, 4.3.6001 for panel | V2 | |

### POWH BaseSpaces WorkGroup

[NSWHP Private Domain BaseSpace](https://nswhp-pl.aps2.sh.basespace.illumina.com/)
Once log in, on top right corner, choose POWH (green tick) for workgroup, choose Personal for testing. 
Java Exception URL is `https://basespace-launch-east.s3.amazonaws.com`

### IGV configuration on PCs

In some circumstance, IGV genome build cannot be loaded due to the proxy. So, we need to configure IGV to use genome build list stored on health web server. 
The instruction guides of [How to setup IGV for local hosted Genomes](./How_to_setup_IGV_for_local_hosted_Genomes.html)


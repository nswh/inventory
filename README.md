## SEALS Genomics Analysis Pipeline Inverntory List

### POWH BaseSpace

[NSWHP Private Domain BaseSpace](https://nswhp-pl.aps2.sh.basespace.illumina.com/)
Once log in, on top right corner, choose POWH (green tick) for workgroup, choose Personal for testing. 
Java Exception URL is `https://basespace-launch-east.s3.amazonaws.com`

### GAIA 3.1.0 - internal only for NovaSeq GRCh38/hg38

[Genomics Annotation Interpretation Analysis pipeline (GAIA 3.1.0)](http://192.168.106.148:3838/gaia/)

POWH_2X-03 onwards

What's New? 
GAIA v3.1.0

gaia-cromwell
Take BaseSpace's converage_vc_metircs.csv file either based on run level or longitudinal collated level.

gaia-init-ref-files
Take BaseSpace's converage_vc_metircs.csv file for 112 AGRF unrelated parents as internal background.

gaia-writesql
RSQLite package installation. final update Ying. Added README.md Take HET_HOM,TS,TV from BaseSpace's converage_vc_metircs.csv file.

gaia-shiny
rlang package 0.4.6 Push to docker repository. Take HET_HOM,TS,TV from BaseSpace's converage_vc_metircs.csv file to replace GAIA's calculation. Take other metrics from BaseSpace's converage_vc_metircs.csv file to display in GUI and HTML report. Show % for gnomAD percentage filter. Expand display of database names. Change internal AC from 10 to 4. Use 'No Filters' in sliding bar. Change 'PubMed + OMIM' to 'No PubMed / No OMIM'. Remove 'Unknown' in pedigree creation pane. The logic behind trio, quartet (with parents), couple etc. does not look for affectness. So leave Unknown won't affect the result. For singleton, duo, cohort, affectness will affect the result. So need to be careful of. Overall, gender only affects Xlinked model. Incorrect selection will make incorrect result for these particular models. Parents gender have to be specified, this is programmed as if leave Unknown will have error.


### GAIA 3.0.3 - internal only for NovaSeq GRCh38/hg38

[Genomics Annotation Interpretation Analysis pipeline (GAIA 3.0.3)](http://192.168.106.148:3839/gaia/)

POWH_2X-02

POWH_2X-01

POWH_NovaSeq6000_20200424

POWH_NovaSeq6000_20200409


### GAIA 2.3 - internal only

1. [Genomics Annotation Interpretation Analysis pipeline (GAIA)](http://192.168.106.108:3838/GAIA_proton/)

2. [Genomics Annotation Interpretation Analysis pipeine (GAIA) - AGRF / Illumina](http://192.168.106.108:3838/GAIA_illumina/)

3. [Quality Metrics Pipeline](http://192.168.106.199:3838/qc/)

### Standalone PubMed search - both internal & external

[PubMed Search (internal; unlimited)](http://192.168.106.108:3838/PubMedSearchTest/)

[PubMed Search (external; 25 hrs/mnth)](https://zhucius.shinyapps.io/PubMedSearchTest_hotfix/)

[PubMed Search (external; unlimited; user's IP address registered)](http://54.252.191.141:3838/pubmedsearchtest/)

Please only use the external PubMed Search when working from home or if the internal one becomes unresponsive.

----------------------------------------------------------------------------------------------------------------------------
## How can I access .bam files for AGRF samples?
All AGRF data is located on the PromisePegasus storage array. To access those files, you need to "mount" this storage into your computer. The instructions for doing this differ per operating system

### Windows
You can mount PromisePegasus through the following steps:

1. Open up a new Explorer window (the folder icon on the start bar)
2. Go to “This PC”, Right click under Network locations and select “Add a network location”
3. Click Next, then click on “Choose a custom network location” to highlight it before clicking Next again
4. Type in the address `\\192.168.106.134\PromisePegasus\AGRF` and click Next.
5. Enter credentials:
      * username: `seals`
      * password: `sealsgenetics`
6. Choose a name for the folder (e.g. AGRF) and click Next. Click Finish.

### Mac OSX

You can mount PromisePegasus through the following steps:

1. Open up a new Finder window (the smiley blue-and-white icon on the Dock)
2. On the left side, locate "Tony's iMac Pro" and click it
3. Under the logo of a display, click "Connect As..."
4. Select "Registered User" and enter credentials:
      * username: `seals`
      * password: `sealsgenetics`
5. Navigate to the "PromisePegaus > AGRF" folder

----------------------------------------------------------------------------------------------------------------------------
## Where can I find backups of samples?

| Disk    | From    | To      | Back up date | Intersect date | Notes                                                                                                                                                |
|---------|---------|---------|--------------|----------------|------------------------------------------------------------------------------------------------------------------------------------------------------|
| Disk 0  | JUP_0   | JUP_79  | 29/3/17      | 29/3/17        | Up to JUP-78, the BAM files are also on this disk. From JUP-82 no BAM files on this backup. Please refer to other disks for those BAM files.         |
| Disk 1  | JUP_80  | JUP_91  | 19/10/15     | 29/3/17        |                                                                                                                                                      |
| Disk 2  | JUP_92  | JUP_104 | 3/3/16       | 29/3/17        |                                                                                                                                                      |
| Disk 3  | JUP_105 | JUP_120 | 3/8/16       | 29/3/17        |                                                                                                                                                      |
| Disk 4  | JUP_121 | JUP_136 | 31/10/16     | 29/3/17        | JUP_128 was not backed up. Run was a complete failure due to an IC error.                                                                            |
| Disk 5  | JUP_137 | JUP_152 | 29/12/16     | 29/3/17        | JUP-151 chip failed. Data not kept                                                                                                                   |
| Disk 6  | JUP_153 | JUP_166 | 5/5/17       | 21/12/17       | JUP_165 aka TEST2_365; JUP_166 aka TEST_360; From JUP_163 only BAM, gvf and vcf files backed up                                                      |
| Disk 7  | JUP_167 | JUP_220 | 15/12/17     | 21/12/17       | Note: Jup 183 and 184 not backed up as they failed. Templating issue on the IC                                                                       |
| Disk 8  | JUP_221 | JUP_288 | 5/6/18       | 13/6/18        |                                                                                                                                                      |
| Disk 9  | JUP_289 | JUP_348 | 15/10/18     | 2/11/18        |                                                                                                                                                      |
| Disk 10 | JUP_354 | JUP_395 | 14/1/19      | -              | JUP_349 to JUP_353 Inclusive were not backed up due to poor data output as a result of underseeding of the Ion Chef template for each of those runs. |
| Disk 11 | JUP_396 | JUP_450 | 29/1/19      | -              | JUP_448 has reanalysis in the next disk. |                                                                                                                                                     | Disk 12 | JUP_451 | JUP_507 |              |                | JUP_448 reanalysis is in this disk. |
| Disk 13 | JUP_543 | JUP_565 |              |                |
| Disk 14 | JUP_566 | JUP_619 |              |                |

----------------------------------------------------------------------------------------------------------------------------
### Error Log Form Entry - both internal & external

[Please Log the Error HERE](https://forms.gle/1QHq86jYwpFt8qqY8). Please DO NOT type in patient information! 

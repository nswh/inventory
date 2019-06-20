## SEALS Genomics Analysis Pipeline Inverntory List


### Primary Pipeline - internal only

1. [Genomics Annotation Interpretation Analysis pipeline (GAIA)](http://192.168.106.132:3838/myapp/)

2. [Genomics Annotation Interpretation Analysis pipeine (GAIA) - AGRF](http://192.168.106.132:3838/myapp_agrf/)

3. [Quality Metrics Pipeline](http://192.168.106.199:3838/qc/)
4. [sandbox Quality Metrics Pipeline](http://192.168.106.201:3838/qc/) For validation purpose. 


### Standalone PubMed search - both internal & external

[PubMed Search (internal; unlimited)](http://192.168.106.146:3838/PubMedSearchV04/)

[PubMed Search (external; 25 hrs/mnth)](https://sealsgenetics.shinyapps.io/PubMedSearch/)

Please only use the external PubMed Search when working from home or if the internal one becomes unresponsive.


----------------------------------------------------------------------------------------------------------------------------
### Error Log Form Entry - both internal & external

[Please Log the Error HERE](https://forms.gle/1QHq86jYwpFt8qqY8). Please DO NOT type in patient information! 


----------------------------------------------------------------------------------------------------------------------------
### Where can I find backups of samples?

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
| Disk 11 | JUP_396 | JUP_405 | 29/1/19      | -              |                                                                                                                                                      |

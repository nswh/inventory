## What's New?

GAIA v3.1.0

* gaia-cromwell

Take BaseSpace's converage_vc_metircs.csv file either based on run level or longitudinal collated level.

* gaia-init-ref-files

Take BaseSpace's converage_vc_metircs.csv file for 112 AGRF unrelated parents as internal background.

* gaia-writesql

RSQLite package installation. final update Ying. Added README.md Take HET_HOM,TS,TV from BaseSpace's converage_vc_metircs.csv file.

* gaia-shiny

rlang package 0.4.6 Push to docker repository. Take HET_HOM,TS,TV from BaseSpace's converage_vc_metircs.csv file to replace GAIA's calculation. Take other metrics from BaseSpace's converage_vc_metircs.csv file to display in GUI and HTML report. Show % for gnomAD percentage filter. Expand display of database names. Change internal AC from 10 to 4. Use 'No Filters' in sliding bar. Change 'PubMed + OMIM' to 'No PubMed / No OMIM'. Remove 'Unknown' in pedigree creation pane. The logic behind trio, quartet (with parents), couple etc. does not look for affectness. So leave Unknown won't affect the result. For singleton, duo, cohort, affectness will affect the result. So need to be careful of. Overall, gender only affects Xlinked model. Incorrect selection will make incorrect result for these particular models. Parents gender have to be specified, this is programmed as if leave Unknown will have error.

[back](./)

# wgs_pipeline_on_hg19

whole human genome sequence alignment/mapping pipeline on hg19 reference genome 

reference genome and public databases were downloaded from broadinstitute official ftp server

wget -m -N ftp://gsapubftp-anonymous@ftp.broadinstitute.org/bundle/2.8/hg19 # currently link is changed 

gatk version used in this pipeline is 3.8-1-0-gf15c1c3ef

### list of files:

- .gitignore
- bash_pipeline.sh - sample of script generated by wgs_pipeline_on_hg19.py
- CHANGELOG.md - list of changes as pipeline developed
- environment.yml - instructions for new conda environment
- README.md - this file
- sswgsap.py - old version of pipeline, old format
- wgs_pipeline_on_hg19.py - full version of pipeline, new format
 
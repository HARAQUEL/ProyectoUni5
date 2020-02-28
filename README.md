Contains data and scripts for the project unit 5


### `/bin/`
All scripts were run in the CONABIO'cluster. The scripts should be run in order they are numbered. 

Scripts content: 
*`1.Download_data` permit create directories and download the wolves data in vcf format from the repository: Schweizer RM, Robinson J, Harrigan R, Silva P, Galaverni M, Musiani M, Green RE, Novembre J, Wayne RK (2015) Targeted capture and resequencing of 1040 genes reveal environmentally driven functional variation in gray wolves. Dryad Digital http://dx.doi.org/10.5061/dryad.8g0s3

*`2.Resolve_questions` provide the commands for resolve the questions about populations genetics from wolves data downloaded. Contains the instructions to convert to plink format. IMPORTANT: The absolute path used with docker and VCFtools should be change to the path of the own computer 

These scripts use the information in `data`

### `/data/` 
Contains wolves genetic data obtained from targeted capture and resequencing of 1040 in gray wolves (available in repository http://dx.doi.org/10.5061/dryad.8g0s3)

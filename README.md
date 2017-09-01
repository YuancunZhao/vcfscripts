# vcfscripts

This is a bash shell script for genotypes outputting through vcf files based on 1000 Genomes Project using VCFtools.

To run this script, please copy it to the directory that contains the vcf files of 1000 Genomes Project phase 3 data and change dorectory (cd) to this dorectory under bash shell.

Command
```Bash
$ sh genotype_output.sh
```
would run the script.

Example loci information and population abbreviations shoud be replaced by customized loci information and population abbreviations by editing our script using text editor (e.g. vim, Sublime Text et al.). Other wise, the genotypes of four SNPs (rs2894257, rs9265769, rs7767914, and rs9350317) under chromosome 6 in four populations (GBR, ACB, ASW, and BEB) would be outputted.
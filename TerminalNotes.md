Helpful tips when using the terminal on saturn cloud:

- Each command to work, we must click enter.
- When writing file names, you can write the first letter, then click tab.
- **clear** command used to clear the terminal from previous written commands.
- **ls** command is used to list and show us what files are there in the current folder.
- **head** command is used to prints out the first ten lines of a file by default ( we used it to view the binary file which was compressed)
- **gunzip** : uncompress FILEs (by default, in-place), -k : keep (don't delete) input files ( we used gunzip –k).
- **wget** : command used to download files  : wget+space+ file+enter 
- **cd** : change working directory.
- **mv** to move files.
- Use **sudo** before commands such as **mv** to give permission if it was denied.

To intsall **less** :

1- sudo apt-get update

2- sudo apt-get upgrade

3- sudo apt-get install less

If you see eta, it  means  estimated time to arrival. 

What we need to write in the terminal (download the files, and uncompress the vcf zip file):

wget ftp://ftp.1000genomes.ebi.ac.uk/vol1/ftp/release/20110521/ALL.chr22.phase1_release_v3.20101123.snps_indels_svs.genotypes.vcf.gz

wget ftp://ftp.1000genomes.ebi.ac.uk/vol1/ftp/release/20110521/ALL.chr22.phase1_release_v3.20101123.snps_indels_svs.genotypes.vcf.gz.tbi

wget ftp://ftp.1000genomes.ebi.ac.uk/vol1/ftp/release/20110521/phase1_integrated_calls.20101123.ALL.panel

gunzip -k ALL.chr22.phase1_release_v3.20101123.snps_indels_svs.genotypes.vcf.gz


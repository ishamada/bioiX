Helpful tips when using the terminal on saturn cloud:
- Each command to work , we must click enter
- When writing file names, you can write the first letter , then click tab .
- Clear command used to clear the terminal from previous written commands
- Ls  command is used to show us what files are there in the our folder
- head command is used to prints out the first ten lines of a file by default ( we used it to view the binary file which was compressed)
- Gunzip Uncompress FILEs (by default, in-place), -k : keep (don't delete) input files ( we used gunzip –k)
- Wget command used to download files  : wget+space+ file+enter 
- cd : change working directory
- mv to move files
- Use sudo before commands such as mv and cd to give permission if it was denied
To use less : 
1- Sudo apt-get update 
2- Sudo apt-get upgrade 
3- Sudo apt-get install less
less
If you see Eta, it  means  estimated time to arrival 

what we need to write in the terminal ( download the files, and uncompress the vcf zip file)
wget ftp://ftp.1000genomes.ebi.ac.uk/vol1/ftp/release/20110521/ALL.chr22.phase1_release_v3.20101123.snps_indels_svs.genotypes.vcf.gz
wget ftp://ftp.1000genomes.ebi.ac.uk/vol1/ftp/release/20110521/ALL.chr22.phase1_release_v3.20101123.snps_indels_svs.genotypes.vcf.gz.tbi
wget ftp://ftp.1000genomes.ebi.ac.uk/vol1/ftp/release/20110521/phase1_integrated_calls.20101123.ALL.panel
gunzip -k ALL.chr22.phase1_release_v3.20101123.snps_indels_svs.genotypes.vcf.gz


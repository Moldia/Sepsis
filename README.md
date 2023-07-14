Repository including scripts related to the MIP-based NGS assay for identification of pathogens and AMR genes 

Install Perl
Install ActivePerl https://www.activestate.com/products/perl/
Install parallel fork manager https://code.activestate.com/ppm/Parallel-ForkManager/


Create new folder with the data of analysis


Change folder names to this structure (use Renamer (https://www.den4b.com/products/renamer)):
Sample_01_D1
Sample_10_D1


Change file names to this structure:


Sample01_S1_L001_R1_001.fastq.gz
Sample10_S10_L001_R1_001.fastq.gz


Copy the following files to that folder:


Scripts
%Folder containing the running scripts for the pipelibe


AdapterFW.txt
%Sequence of the forward primer(s) used for probe amplification 


barcodes.tsv
%List of the target names and corresponding barcodes

 
PATH_TAGS.txt
%List of the barcodes/target (just sequences)


pipeline.pl
%running pipeline


pipeline-serial.pl
%running pipeline for analysis of multiple samples in paralell


postprocessing.pl
%running pipeline for postprocessing, generates the heat map


single-sample-target-count-pl
%running pipeline that calculates reads/probe for selected samples

Target_list.txt
%complete probe target list




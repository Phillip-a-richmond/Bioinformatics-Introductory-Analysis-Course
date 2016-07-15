## In Class Assignment Section 8 & 9: RNA-seq analysis
>This section will focus on analysis of an RNAseq dataset in Vitis Vinifera



### Part I (Acquire data from the SRA, and run quality analysis on the fastq files you download)
1. Create an Assignment 8and9 directory in /global/scratch/richmonp/WRC/
2. Download two conditions (3 replicates each) of RNAseq data from from the same grape vine using fastq.dump [publication](http://bmcplantbiol.biomedcentral.com/articles/10.1186/s12870-016-0760-1) 
http://bmcplantbiol.biomedcentral.com/articles/10.1186/s12870-016-0760-1 
fastq.dump is located here: /global/scratch/richmonp/TOOLS/sratoolkit.2.6.3-centos_linux64/fastq.dump
3. Document where you got the files from in a README.txt.
4. Change the names of the files to match their sample ID: <day_type_replicate>.fastq, and add your renaming changes to the README.txt
5. Run FastQC on each of the fastq files you downloaded, and interpret the results


### Part II (Map with tophat2, assemble transcripts using cufflinks, merge with cuffmerge, and get differential expression using cuffdiff) 
> These steps must all be completed via the queue, since the files are too large to run on the head node.
> There are example PBS scripts for these commands in: /global/scratch/richmonp/WRC/

1. Map with tophat2, and alter some options including trying out:
--b2-very-sensitive, number of mismatches, total number of alignments to report, etc.
2. Run cufflinks per mapped bam file to generate a transcripts.gtf file
3. Run cuffmerge on all your gtf files (don't forget to include the reference GTF with the -g option)
4. Run cuffdiff on the cuffmerge gtf file between each condition you want to compare.  How many differentially expressed (DE) genes are there?  In the cuffdiff output directory, look at the gene_exp.diff.  (You can grep "yes" from this file to see how many are called DE at a given cutoff).
5. Does this number change if you use the merged transcripts?


The End :)


## In Class Assignment Section 5: Introduction to mapping
>This section will focus on the basic operations that you will use in the linux/unix environment, all run from the terminal.

### Part I (Read mapping of lambda paired end reads)
1. Create an Assignment 5 directory called: \<LastName\>_Assignment5
2. Copy the files from:  /global/scratch/WRC/Data/Assignment_5_Files/ into your Assignment 5 directory
3. Using bowtie2-build, create a new index of the lambda genome called Assignment5_Lambda_Bowtie2_Index
4. Map the paired end reads (Assignment_5_1.fq, Assignment_5_2.fq) back to the reference genome
5. How many of the pairs mapped concordantly back to the genome?
6. Save the standard error from the mapping in a file called: Assignment5_lambda_bowtie2.stderr
7. Convert the output sam file into bam format using samtools
8. Sort the bam file using samtools
9. Index the bam file using samtools
10. Copy all the commands you ran above into a shell script, and call it: \<LastName\>_Process_Assignment_5.sh
11. Execute the shell script to make sure it works


### Part II (Visualizing the mapped reads)
1. Download the fasta, sorted bam, and index file onto your local machine
2. Open up IGV on your local machine, and create a lambda genome 
3. Load the reads you just mapped to the lambda genome in IGV
4. Take a snapshot of the mapped reads, and email this snapshot plus the shell script from Part I to: phillip.a.richmond@gmail.com

### Part III (Project Organization)
1. Reorganize your Assignment 5 directory using the scheme in the slides from Section I-6.
2. Create a README.txt file in every directory detailing where you got the files from, and the date at which you got them.


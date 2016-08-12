### Bioinformatics-Introductory-Analysis-Course
Welcome to Introduction to Bioinformatics Analysis, a course taught by Phillip A Richmond.  

#### Course Purpose
>The purpose of this course is to provide an introduction to Bioinformatics and Genomics as it pertains to short-read sequencing analysis, with a specific focus on brewing and fermentation yeast strains.  Taught in an inverted classroom format, there will be screencasts and lecture notes for each section that can be gone through independently, and in class we will simply work on example datasets and problem sets.

***

#### General Course Information & Prerequisites
The course is intended for academic researchers at Canadian institutions in Western Canada, that have access to nationally supported Research Computing through Compute Canada, specifically the WestGrid branch.

+ Prerequisites
  + WestGrid access is required, and is different for a PI vs. a student
    + Westgrid Account information [here](https://www.westgrid.ca/support/accounts/getting_account)
    + For a Westgrid Account, register by following these [instructions](https://www.computecanada.ca/research-portal/account-management/apply-for-an-account/).  Realize that the process can take several days!  
  + GitHub Account 
    + It's free, and you can sign up [here](https://github.com/) 
  + For mac/linux users, only need native terminal which comes with the operating system 
  + For PC users, download and install [MobaXterm](http://mobaxterm.mobatek.net/) 
    + [Advanced MobaXterm usage](https://www.youtube.com/watch?v=Gkl8LD1rwlU) 
  + IGV installed on local machine 
    + [IGV install](https://www.broadinstitute.org/software/igv/log-in) 
+ General Course Info 
  + Videos are hosted via YouTube at Phil Richmond's YouTube Channel [here](https://www.youtube.com/channel/UC6B7cpEwSZTdbPd0d9G2JXg) 
  + Slides, Assignments, and Quizzes are hosted via Google Drive  [here](https://drive.google.com/drive/u/0/folders/0B3TGYF-7rCLnWjFJRVlHcVN5Nk0) 
  + Extra resources:
    + [Linux/Unix Cheatsheet](https://github.com/Phillip-a-richmond/Bioinformatics-Introductory-Analysis-Course/blob/master/UnixCheatSheet.pdf) 
    + [Linux/Unix online tutorial](http://www.ee.surrey.ac.uk/Teaching/Unix/) 
    + Editor cheat sheets 
      + [Emacs cheet sheet](http://www.rgrjr.com/emacs/emacs_cheat.html) 
      + [vi cheat sheet](http://www.lagmonster.org/docs/vi.html) 
      + [nano cheat sheet](http://www.codexpedia.com/text-editor/nano-text-editor-command-cheatsheet/) 
    + File transfer programs  
      + [Cyberduck](http://download.cnet.com/Cyberduck/3000-2160_4-10246246.html) 
      + [WinSCP](https://winscp.net/eng/download.php) 
    + WestGrid resources 
      + [WestGrid website](https://www.westgrid.ca/) 
      + [Running jobs](https://www.westgrid.ca/support/running_jobs) 
      + [Software available](https://www.westgrid.ca/support/software/) 
      

***

#### Course Schedule (Round 2!  Vivien and Simone) FNH100A
1. Monday August 15th, 2016.  
  2:00 PM - 4:00 PM.  
  Section I-1, Section I-2, Section I-3a  

2. Tuesday August 16th, 2016  
  9:30 AM - 11:30 AM  
  Section I-3a finish, Section I-3b 

3. Wednesday August 17th, 2016  
  9:30 AM - 11:30 AM  
  Section I-4 
 
4. Thursday August 18th, 2016  
   9:30 AM - 11:30 AM  
   Section I-5, I-6  

5. Friday August 19th, 2016  
   9:30 AM - 11:30 AM  
   Section I-7  

***

#### Course Outline
##### Section I: Introductions, Linux/Unix, WestGrid, Short Read Mapping, PBS Queue Scheduler
1. Introduction to Next Generation Sequencing, Bioinformatics, and Computing
  + [Slides](https://drive.google.com/open?id=0B3TGYF-7rCLnR3VDeENSc1NHbFU)
  + [Video](https://www.youtube.com/watch?v=gC2o1U9qgtg&index=3&list=PLeqoVMkuHVTckmVUIhPjWFDn2Ci2t5Z0S)
2. Getting set-up on WestGrid and using terminal
  + Open up a terminal
  + Customize terminal
  + Login to WestGrid 
  + [Specs of Orcinus](https://www.westgrid.ca/support/systems/Orcinus)
  + [Slides](https://drive.google.com/open?id=0B3TGYF-7rCLnZU5TYzdZLUlXZG8)
  + [Video](https://www.youtube.com/watch?v=kaAAhId5HD8&list=PLeqoVMkuHVTckmVUIhPjWFDn2Ci2t5Z0S&index=1)
  + [PC User MobaXterm guide](https://www.youtube.com/watch?v=Gkl8LD1rwlU)
  + [In Class Assignment Section I-2](https://github.com/Phillip-a-richmond/Bioinformatics-Introductory-Analysis-Course/blob/master/Assignments/InClassAssignmentSection2.md)
  + Total in class time: 30 minutes
3. Exploring Linux/Unix
  + Intro to linux environment (3a)
    + ls, mkdir, cp, mv, rm, cat, more, less
    + Man pages
    + File creation
    + [Slides](https://drive.google.com/open?id=0B3TGYF-7rCLncEZPbVFqa29nWUE)
    + [Video](https://www.youtube.com/watch?v=pxxt8PrStio&feature=youtu.be)
  + Intermediate Linux commands (3b)
    + head, tail, sort, cut, paste, df, du, grep, find, permissions
    + [Slides](https://drive.google.com/open?id=0B3TGYF-7rCLnbFRFNk03V0h6QkE)
    + [Video](https://www.youtube.com/watch?v=08g3HZb0NRw)
  + [In Class Assignment Section I-3](https://github.com/Phillip-a-richmond/Bioinformatics-Introductory-Analysis-Course/blob/master/Assignments/InClassAssignmentSection3.md)
  + For more practice, do [these exercises](http://www.ee.surrey.ac.uk/Teaching/Unix/index.html)
4. Advanced Linux/Unix
  + File Management
    + Compression
    + Downloading (wget)
    + Remote Copy (scp)
  + File Editing
    + vi, emacs, nano: Pick emacs
    + [Emacs cheet sheet](http://www.rgrjr.com/emacs/emacs_cheat.html)
    + [vi cheat sheet](http://www.lagmonster.org/docs/vi.html)
    + [nano cheat sheet](http://www.codexpedia.com/text-editor/nano-text-editor-command-cheatsheet/)
  + Other Secure Copy programs
    + [Cyberduck](http://download.cnet.com/Cyberduck/3000-2160_4-10246246.html)
    + [WinSCP](https://winscp.net/eng/download.php)
  + [Slides](https://drive.google.com/drive/folders/0B3TGYF-7rCLnWjFJRVlHcVN5Nk0)
  + [Video](https://youtu.be/r9zJCo42gl8)
  + [In Class Assignment](https://github.com/Phillip-a-richmond/Bioinformatics-Introductory-Analysis-Course/blob/master/Assignments/InClassAssignmentSection4.md)
5. Intro to Read Mapping and Data Visualization
  + Bowtie2 & Samtools (5a)
    + Build genome index
    + Map paired reads
    + Interpret standard error
    + Convert bam 2 sam (samtools index)
    + Sort bam (samtools sort)
    + [Slides](https://drive.google.com/drive/folders/0B3TGYF-7rCLnWjFJRVlHcVN5Nk0)
    + [Video](https://www.youtube.com/watch?v=MPQ7F1EfEdE&index=4&list=PLeqoVMkuHVTckmVUIhPjWFDn2Ci2t5Z0S)
  + Data visualization (5b)
    + Integrative Genomics Viewer (IGV)
    + [Slides](https://drive.google.com/drive/folders/0B3TGYF-7rCLnWjFJRVlHcVN5Nk0)
    + [Video](https://youtu.be/LDD8PKKtWuY)
  + [In Class Assignment](https://github.com/Phillip-a-richmond/Bioinformatics-Introductory-Analysis-Course/blob/master/Assignments/InClassAssignmentSection5and6.md)
6. Organization and file naming  
  + Hierarchical organization 
  + File naming and suffixes 
  + [Slides](https://drive.google.com/drive/folders/0B3TGYF-7rCLnWjFJRVlHcVN5Nk0) 
  + [Video](https://www.youtube.com/watch?v=vwoEZ-KU1ds&index=8&list=PLeqoVMkuHVTckmVUIhPjWFDn2Ci2t5Z0S) 
7. Interacting with the queue 
  + Job Submission 
  + Job Tracking 
  + [WestGrid Job Running Resource](https://www.westgrid.ca/support/running_jobs)
  + [Slides](https://drive.google.com/drive/folders/0B3TGYF-7rCLnWjFJRVlHcVN5Nk0)
  + [Video](https://www.youtube.com/watch?v=pde6fk8wqr4&feature=youtu.be)
  + [In Class Assignment](https://github.com/Phillip-a-richmond/Bioinformatics-Introductory-Analysis-Course/blob/master/Assignments/InClassAssignmentSection7.md)

***

##### In class test
> The in-class test will be an individual examination, so you won't be able to work together in groups for it.  The test will be comprehensive for all the things we learned in Section I, and if you are able to complete the assignments for each section, then the test should take only ~ 30 minutes.  You will have a 2 hour block to complete the test.  If you are unable to do so, then you won't be able to move on to Section II.  

***

##### Section II: Introduction to Applied Genomics: Acquiring Data, Raw data QC, Variant Calling, Assembly, RNAseq
**NOTE** For section II, you will need to ask WestGrid for special access to the high memory servers: Hungabee, Breezy. 
Email: Support@Westgrid.ca
8) Getting data from the SRA, Raw Data QC
  + Short read archive & fastq.dump
  + FastQC
  + Trimmomatic
  + [Slides](https://drive.google.com/open?id=0B3TGYF-7rCLnOV9fMDZfTmE5cDg)
  + Video
9) RNAseq (grape vine) 
  + TopHat
  + Cufflinks --> Cuffmerge --> Cuffdiff
  + [Slides](https://drive.google.com/open?id=0B3TGYF-7rCLnNjBiTGxYZFdIVVE)
  + Video
  + [In Class Assignment](https://github.com/Phillip-a-richmond/Bioinformatics-Introductory-Analysis-Course/blob/master/Assignments/InClassAssignmentSection9.md)
10) Transposon Insertion Profiling (TIP-seq)
  + Initial Processing (10a)
    + Clean up reads
    + Map with BWA
    + Samtools Unique mapped
    + Remove duplicates
    + Visualize
    + Slides
    + Video
  + Differential Insertion (10b)
    + Call Peaks
    + Differential Insertion Analysis
    + Slides
    + Video
11) Transcriptome Assembly
  + Trinity
  + Trans-Abyss
  + Slides
  + Video
  + In Class Assignment
12) Variant Calling (Saccharomyces cerevisiae)
  + Map with BWA
  + Samtools mpileup
  + Picard MarkDuplicates
  + Samtools Unique Reads
  + Visualize in IGV
  + Slides
  + Video
  + In Class Assignment

##### Section III: BYOD (Bring your own datasets)
This section is open to those who want to explore their own datasets and receive help with processing and data analysis.  


***


Feedback?  Suggestions?  Don't hesitate to contact me:

Course Instructor | Affiliation | Email Address(es) | github ID | Phone Number
--- | --- | --- | --- | ---
Phillip Richmond | PhD Student, Bioinformatics, UBC | prichmond@ubc.ca or phillip.a.richmond@gmail.com | [@Phillip-a-Richmond](https://github.com/Phillip-a-richmond) | (604)655-3595


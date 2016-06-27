## In Class Assignment Section 3: Exploring Linux/Unix

>This section will focus on the basic operations that you will use in the linux/unix environment, all run from the terminal.

### Part I (pwd, ls, man, touch, cd, mkdir, mv, rm)

1. Login to Orcinus.   What is the name of your home directory?
2. Within your home directory, make a directory called: TypesOfWine
3. Change into the directory that you just created.
4. Make a new directory inside of TypesOfWine called: Reds
5. Make another directory inside of TypesOfWine called: Whites
6. Change into the Whites directory, and make an empty file called (hint: $ touch <filename>) : Cabarnet_Sauvignon
7. Wait a minute, the spelling doesn't seem right here.  Change the name of the file to be: Cabernet_Sauvignon
8. It takes a real fool to think that this is a type of white wine.  Move this file into the Reds directory.
9. Go back to your home directory, and list out all the files in a recursive manner (hint: man ls).
10. Change into the /global/scratch/WRC/ directory.
11. Make your Assignment 3 directory named: \<YourLastName\>_Assignment3. (For me it's Richmond_Assignment3)
12. Change into the TypesOfWine directory in the /global/scratch/WRC/ parent directory. 
13. Create a new file titled: \<lastname\>_\<typeOfWine\>.txt.  Make sure you don't reuse a type of wine that someone else has already listed  (Note: When you see me use characters like this, I want you to replace what's in the <> with your own information, ex: Richmond_Malbec.txt)
14. It's bad practice to have the same directory names in multiple places.  Go back to your home directory and change the name of your TypesOfWine directory to: Types_of_Wine

### Part II (wc, cat, more, less, head, tail, cut, paste, grep, chmod)
  > Note: All the work for part II should take place in your Assignment 3 directory

1. Copy this file into your Assignment 3 directory: /global/scratch/WRC/Assignment_3_Files/S288c.gff
2. This gff file has both sequence and annotation in it.  We only want to keep the top of this file, up until the first fasta sequence entry.  Find the first fasta sequence entry with grep. (hint, to figure out how to print the line number look at the grep manual)
3. Create a new file that has all the annotation information, without any of the fasta sequence.  Save this file as S288c_fixed.gff  (hint, we want the top of the file all the up way up a certain line #)
4. Extract all the annotations for chromosome twelve from this file, and save it as: S288c_chrXII.gff  (hint, Look at the grep manual, we don't want to capture any chrXIII lines)
5. How many genes are there on chromosome 12?
6. Of these genes, how many of them are Dubious?
7. Let's say that we don't want to include Dubious genes, they just sound problematic!  Grab all the non-Dubious genes from S288c_chrXII.gff and put them in a new file called: S288c_chrXII_nonDubious_genes.gff (hint, look at grep manual to find non-match lines)
8. Fill out this table with the appropriate values, using the same processes you did in problems 4-7:

  | Chromosome    | Number of Annotations | Number of Genes  | Number of non-Dubious Genes |
  | :------------- |:-------------:| -----:|----:|  
  | chrXII        |   |  |  |
  | chrIV         |   |  |  | 
  | chrmt         |   |  |  |

9. Create a simple bed file (chromosome  start   stop) for all the CDS entries on chrI, an save it as: S288c_chrI_CDS.bed
10. Add on the strand information for these CDS annotations using the paste command, and create a new file called: S288c_chrI_CDS_withStrand.bed
11. The annotations the file you just created go from low to high on the chromosomal position.  Re-sort this file so that the annotations go from high to low.  (Hint, use the internet, I never taught you sort)
12. Change the permissions on your Assignment 3 directory to allow the user, group, and world to read, write and execute.
13. Change the permissions on the S288c_chrI_CDS.bed to be read, write, and execute for the user, but only readable for the group and world.

When you are done, show Phil your Assignment 3 directory, and then help others who are still working/struggling/pulling their hair out.










## In Class Assignment Section 7: Interacting with the queue
>This section will focus on the interacting with the job scheduler, AKA the queue.


### Part I (Submit to the queue)
1. Create an Assignment 7 directory called: \<LastName\>_Assignment7
2. Copy the example header PBS script into your Assignment 7 directory, and edit the file to replace the fake email address with your actual email address.
3. Copy the MapAndConvert.sh script from your Assignment 5 directory to your Assignment 7 directory.  If you didn't do Assignment 5, go do it now!  
4. Concatenate these files together to create a single file called: MapAndConvert.pbs
5. Submit this script to the queue.
6. Check the status of your script.
7. When it's finished, forward the email you received from it's completion to: Phillip.a.richmond@gmail.com


### Part II (Advanced queueing options)
1. Copy the MapAndConvert.pbs script to a new file called: MapAndConvert_PartII.pbs
2. Go to www.westgrid.ca/support/running_jobs, and figure out how to add a job name to the script.  Add the correct PBS line and call your job: \<LastName\>_MapAndConvert
3. Change the number of processors in the job script from 1 to 4.  Also change the number of processors in the bowtie2 command to be equal to 4 (hint: Bowtie2 manual-->multithreading/parallel processor option)
4. Change the memory allocation from 2Gb to 4Gb.
5. Change the allowed maximum walltime from 15 minutes to 15 hours.
6. Submit this script to the queue.
7. Check the status of your script.





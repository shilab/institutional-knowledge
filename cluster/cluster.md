Working on the clusters
-----

Submit jobs using ```qsub sub.sh``` where sub.sh is the submission script.  
You will see an output like ```425111.vpr-m3.uncc.edu```, where the number is the jobid.

Check on job status using ```qstat```. You will see output like: ```424936.vpr-m3              vcf_split        aquitada        01:20:14 R viper```
The first column has the jobid, the second column is the job name, the third column is your user name, the fourth is the time running, the fifth is the job status.
The job status is Q for queued, R for running or C for complete. 
You can get the full job status by using ```qstat -f jobid```.

Delete a running job by using ```qdel jobid```.

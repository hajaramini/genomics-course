# genomics-course
report.txt, including the output of quast on the assembly from the trimmed reads
history.txt, including the command
By comparing the output of quast on the assembly from the untrimmed reads with trimmed reads we could find out 
There are a little difference between these two results such as 
The # contigs (>= 0 bp, >=1000 bp and >=500 bp) with trimming decreased. Maybe with trimming the contigs of adaptor or other contaminating were removed. Because several changes with trimming happened such as cutting adapter and other illumina-specific sequences from the read or cutting some bases from end of reads. All of these change could be reasons for decreasing # contigs
Overall, trimming gives also an advantage in terms of computational resources used and execution time, reduce the number of sequencing errors input to the assembler and etc.  


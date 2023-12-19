**Project - 01**
I have found the individual on the "international genomes database". Then selected sequencing for the taken population.
And I found out how many variants would you expect them to carry compared to the reference genome in the given population. By the data access, have futher downloaded the exome swquencing for the 
taken population. I performed "Pre-QC by uing FASTQC" followed with "Trimming with fastp or trimmmomatic" then "Post-QC with FastQC".

**Project - 02**
By the previous fastq files, I have aligned the files by minimap2 and created the SAM files for the population. By, using the SAM tool I performed "Post Read alignment" for the SAM files and Sorted the SAM
files. Further, I have converted the SAM files to BAM files.

**Project - 03 (Variant Calling)**
I have used the Pileup format for calling variants from SAM file and created the pileup file. I created the plot for read the count distribution by using python
to provide a graph that shows how many reads are aligning to a specific genomic region could be helpful for determining flags for our variant caller. For the variant calling I have used varscan

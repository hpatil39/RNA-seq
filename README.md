**Project - 01**
I have found the individual on the "international genomes database". Then selected sequencing for the taken population.
And I found out how many variants would you expect them to carry compared to the reference genome in the given population. By the data access, have futher downloaded the exome swquencing for the 
taken population. I performed "Pre-QC by uing FASTQC" followed with "Trimming with fastp or trimmmomatic" then "Post-QC with FastQC".

**Project - 02**
By the previous fastq files, I have aligned the files by minimap2 and created the SAM files for the population. By, using the SAM tool I performed "Post Read alignment" for the SAM files and Sorted the SAM
files. Further, I have converted the SAM files to BAM files.

**Project - 03 (Variant Calling)**
I have used the Pileup format for calling variants from SAM file and created the pileup file. I created the plot for read the count distribution by using python to provide a graph that shows how many reads are aligning to a specific genomic region could be helpful for determining flags for our variant caller. For the variant calling I have used varscan, selected the variant from chromosome 16,2. I have further filtered the extracted variants.

**Project - 04 (Polygenic Risk Scores)**
In the given set of VCF files, I have indexed the VCF files further and extracted the samples. And did annoatation for the variants: finding the importance of the genes from genecards. By using PGS (Polygenic Score)catalog is a resource that contains information about polygenic scores, also known as polygenic risk scores (PRS). And further calculated the polygenic risk scores by providing the graphs.

**Project - 05 (RNA - Seq and Differential Gene Expression analysis)**
I have taken Huntington Disease as my intrest of research and downloaded the data. Performed Quality Control for the selected disease (PRE-QC & POST-QC). Also, perfored multiQC. RNA - Seq analysis: Alignment and quantify, by using SALMON tool. I have preformed RNA Quantification and Differential gene expression. Used R-studio for the visualization and provided the volcano plots.


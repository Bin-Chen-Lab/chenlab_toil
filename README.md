# chenlab_toil
RNA-Seq processing using toil

Generate STAR and RSEM index.

https://hbctraining.github.io/Intro-to-rnaseq-hpc-O2/lessons/03_alignment.html

https://hbctraining.github.io/Intro-to-rnaseq-hpc-O2/lessons/03_alignment.html

In your main directory : 

1. Create a folder named fastq.

2. Put all fastq files under the folder "fastq" and name the file in this style: {sample_id}_[12].fastq. 
   For example, sample MYC with paired-end RNA Seq files should be named as MYC_1.fastq and MYC_2.fastq.
  
3. Prepare a text file (usually exp.txt) with each line containing a sample id. Note: line breaks need to be in Unix!

4. Run the pipeline: chenlab.bulk.rna.seq.pipeline.R exp.txt.

5. After the running, go to folder RData to get your data. 


# What is FastQC?  
FastQC is a quality control tool commonly used in bioinformatics to assess the quality of high-throughput sequencing (HTS) data, primarily from platforms like Illumina, PacBio, and Oxford  
Nanopore.It provides detailed insights into raw sequence reads before downstream analyses such as genome assembly, variant calling, and transcriptome profiling.  
## How to install FastQC on your machine
FastQC can either be installed directy from the website in order to use the graphics user interface, or you can use the command line to install fastqc.
**For ubuntu or linux command lines**
* install the fastqc tool
```
sudo apt update
sudo apt install fastqc
```
* move into the directory where your fastq files are located
* run fastqc on the file
```
fastqc file.fastq
```
* If there are multiple files, such as in the case of forward and reverse reads
```
fastqc file_1.fastq file_2.fastq
```
After running your file(s) through the fastqc tool, it generates a html report for each file. This html report can be viewed by your preferred browser

```
xdg-open fastqc_file.html
```
If it is chrome or firefox
```
google-chrome fastqc_file.html
firefox fastqc_file.html
```

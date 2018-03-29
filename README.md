# __Bio-Courses__

## __Introduction__
This page compiles a list of links to tutorials which have been written by numerous authors for many of the steps involved in whole genome sequence (WGS) analysis of prokaryotic organisms. Some of these steps contain concepts and ideas that are generally applicable to whole genome sequencing of other organisms (e.g. read QC) although in many cases the recommended software would be different. It should be noted that the first step for any aspiring bioinformatician of any level is to build up familiarity with the Linux command line. This will provide access to powerful and flexible tools for and applications.

### Disclaimer
The links and tutorials listed below were not written, and are not owned, by the author of this page unless explicitly noted. We take no responsibility for their maintenance or accuracy.

## __Content__
1. Linux command line
2. Programming
    1. Python
    2. Perl
    3. R
2. Core Concepts in WGS
	1. Whole Genome Sequencing (WGS)
	2. Library Preparation
	3. Sequencing Technology
	4. Coverage
3. Sequencing Reads
    1. Short Reads 
    2. Long Reads
    3. Read QC
3. Mapping and Variant Calling
4. Assembly
4. Assembly QC
5. Annotation
5. Phylogenomics
6. Pangenomics
7. K-mer and related
8. Databases
    1. NCBI
    2. ENA
    3. BIGSdb
    4. Enterobase
9. Servers
	1. EDGE

## __Command-line tutorials__
Familiarity with the Linux command-line is usually the first step for budding informaticians. Many tools are only designed or distributed for Linux-based systems. In addition to this many powerful operations, such as iterating through batches of files, can dramatically reduce and simplify workflows.

-  [Introduction to the command-line](https://swcarpentry.github.io/shell-novice/) (swcarpentry) - this tutorial covers a description of the command line, file operations and some loops and more advanced operations.
 - [Bash for Genomics](http://angus.readthedocs.io/en/2016/GenomicsShell.html) – using bash for genomics data tutorial.

## __Programming__
Picking up a programming language allows for an informatician to be more flexible in how they approach analysis workflows. Scripts can be used to automate many complex tasks in a more bespoke way than loops on the command-line. There are some excellent tutorials online for many languages. Python is considered the most powerful and popular language for bioinformatics. Perl comes in a (debatably) close second. R is often used to perform advanced statistical analyses and to produce publication worthy figures.

### Perl
- [Official Perl tutorial page](https://learn.perl.org/tutorials/) - includes a free book on perl programming
### Python
- [Official python tutorial page](https://wiki.python.org/moin/BeginnersGuide/Programmers) - multiple tutorials for all levels.
### R
- [R for begginers](https://cran.r-project.org/doc/contrib/Paradis-rdebuts_en.pdf) – basic introduction to R and statistical analysis.
- [ggplot2 tutorial](http://r-statistics.co/Complete-Ggplot2-Tutorial-Part1-With-R-Code.html) – an incredibly flexible and powerful family of packages for creating figures using the grammar of graphics.

## __Core Concepts in WGS__
### Whole genome sequencing
### Library preparation
 - [Short read sequencing library perpetration concepts](https://bitesizebio.com/webinar/next-generation-sequencing-library-preparation-concepts-and-tips-and-tricks/) (BitesizeBio)
### Sequencing technology
- [Overview of past and current WGS sequencing technologies](https://www.nature.com/articles/nprot.2016.182)
- [Illumina Sequencing](https://www.youtube.com/watch?v=fCd6B5HRaZ8) (Video)
- [Nanopore](https://www.youtube.com/watch?v=GUb1TZvMWsw)  (Video)
- [PacBio](https://www.youtube.com/watch?v=v8p4ph2MAvI) (Video)
### Coverage
Sequence coverage or depth (depth of coverage) is the number of times a base in the target genome is covered by a read e.g. 30x coverage would mean that, on average, each base in your sample will be coverage by 30 reads.
- [coverage guidelines per application](https://genohub.com/recommended-sequencing-coverage-by-application/) 
## __Types of Reads__
### Short Reads
- [Introduction to paired-end reads](https://era7bioinformatics.com/en/page.cfm?id=1626) – slide intro to paired/mate pair reads.
### Long Reads
- [Intro to long reads and long read technologies](https://angus.readthedocs.io/en/2016/_static/Torsten_Seemann_LRS.pdf) (Slides, Torsten Seeman)
### Read QC
- [Fastqc](https://dnacore.missouri.edu/PDF/FastQC_Manual.pdf) – an introduction to fastqc, a tool for assessing multiple read quality metrics. 
- [Trimmomatic manual](http://www.usadellab.org/cms/uploads/supplementary/Trimmomatic/TrimmomaticManual_V0.32.pdf) -  a tools for trimming reads and removing adapter sequences.
## __Mapping and Variant Calling__
- [snippy](https://github.com/tseemann/snippy/blob/master/README.md) - a tool for mapping (BWA) and variant calling. 
## __Assembly__
- [Short read - assembly tutorial using SPAdes](https://github.com/BacterialCommunitiesAndPopulation/Wednesday18thMay/blob/master/Assembly_Tutorial.md)
- [Long read – Nanopore assembly tutorial](http://angus.readthedocs.io/en/2016/analyzing_nanopore_data.html)
## __Assembly QC__
## __Annotation__
- [Assembly annotation tutorial using prokka](https://angus.readthedocs.io/en/stable/prokka_genome_annotation.html) 
## __Phylogenomics__
- [Pangenome based tree construction](https://github.com/BacterialCommunitiesAndPopulation/Thursday19thMay/blob/master/Thursday_Morning.md)
## __Pangenomics__
- [Building a pangenome using roary](https://github.com/BacterialCommunitiesAndPopulation/Thursday19thMay/blob/master/Thursday_Morning.md)
## __K-mer and related__
## __Databases__
### NCBI
### ENA
### BIGsDB
### Enterobase
## __Servers__
### EDGE

# Piracicaba_ESALQ_2023

New sequencing technologies or NGS have opened the door to massive sequencing of living organisms with the possibility to sequence complex and contiguous genomes using very long reads. Among these technologies, nanopore sequencing stands out for its very low cost, but also for its ever increasing accuracy. A wide range of algorithms has been developed to analyze nanopore data. In this course, we will learn the methods and workflow to analyze raw reads and achieve genome assembly.  
We will see how to obtain nucleotide sequences from electrical signals, see the most commonly used assembly paradigm for long fragments, test and compare several state-of-the-art assemblers, and finally evaluate the quality of the resulting assembly with and without a reference genome.


# Course objectives:  
-To know the advantages and disadvantages of Nanopore sequencing.  
-To know more about the de novo assembly of genomes.  
-To practice and have experience with de novo genome assembly.  

# Program:
session_0: Before the start of the course, students should have installed the necessary software for the course, such as:  
-a virtual machine running Linux os (excpet for Linux and MacOs users).  
-[Anaconda](https://www.anaconda.com/products/distribution)   
Students should be familiar with the [jupyter notebook](https://jupyter-notebook.readthedocs.io/en/stable/examples/Notebook/Notebook%20Basics.html) (type jupyter notebook in your teminal).  
Finaly you should download the program of the course usig git as follow: ->go to the git web site of the course ->clone the course: git clone 'adress'.
Students are invited to follow the session Intro_LINUX using jupyter notebook before the course

session_1: Introduction to Oxford Nanopore; Getting to know the `Fast5` format; Calling reads with `Guppy`.  
session_2: Quality control of fastq reads, Mapping reads against a reference genome with `Minimap2`.  
session_3: Genome assembly with `Minimap2` and `Miniasm`, `Flye` and `Shasta`.  
session_4: Polishing of the assemblies with `Racon` and `Medaka`.  
session_5: Quality of the assemblies with `Quast` and `BUSCO`.  

**Download data**.  
**Session_3**.  
-Corrected reads: https://filesender.renater.fr/?s=download&token=abfa6c11-00e1-43e0-908a-3bff56fb79f9    
-Results for session_3: https://filesender.renater.fr/?s=download&token=9a751a66-ef9f-4871-a691-0cef38a7f705.  
-Quast results: https://filesender.renater.fr/?s=download&token=114177c4-9701-4a2d-95c6-34e6a024245b.    
**session_5**.  
-Assemblies: https://filesender.renater.fr/?s=download&token=df3c6f59-9c42-4643-8c33-715369ff6e86.  
-Quast_results: https://filesender.renater.fr/?s=download&token=e7dacb47-6e66-430e-8874-86d7490a9697.   
-Busco_results: https://filesender.renater.fr/?s=download&token=98f3313c-3676-4118-ab04-fb74e391df9b.  
**Session_6**.  
-Dataset of proteus mirabilis: https://filesender.renater.fr/?s=download&token=8283bc0c-4055-4681-8fe0-62bde6835dfa.  


Romain Guyot, IRD.  
[GenomeCoffea](https://www.genomecoffea.org)

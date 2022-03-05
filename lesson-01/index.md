# Week 1, Friday


## Friday, 2022-Feb-18
In this week, we will have a brief overview of the course structure and content and introduce some basic concepts of statistics. Lecture 1 provides a summary about what is and is not included in the course, what to expect from the course and the diference between BIO210 and MA212. Lecture 2 starts to introduce some basic techniques in descriptive statistics. You can think of the lectures as a recap of what you have already known in the past.

There is no homework today, but please have a look at the practice section below. Can you answer those questions? How did you solve the problems? Is it easy or difficult to do? We will discuss the ways of solving those problems later on. Hopefully, through BIO210, you will also gain some practical skills in terms of text file manipulation, which is actually quite important but missing in many courses.

#### Lecture slides
- [Lecture 1 Introduction To BIO210](/lecture_slides/Lecture_1_Introduction_To_BIO210_handout.pdf)
- [Lecture 2 Data Presentation](/lecture_slides/Lecture_2_Data_Presentation_handout.pdf)

#### Homework assignment
- No homework today.

#### Interesting links
- [Human factors engineering studies of the design and use of pushbutton telephone sets](https://ieeexplore.ieee.org/document/6773609)
- [Expected locations of digits and letters on ten-button keysets](https://psycnet.apa.org/record/1956-07868-001)
- [John Snow - The Father of Epidemiology](https://sphweb.bumc.bu.edu/otlt/mph-modules/ph/publichealthhistory/publichealthhistory6.html)
- [About John Snow](http://johnsnow.matrix.msu.edu/index.php)
- [2D/3D Spot Map](https://ralucanicola.github.io/cholera-map-3D)
- [Cholera Map](https://mjdanielson.github.io/Cholera-Map)

#### Practice
1. A series of publications in 2008 ([Nagalakshmi _et al. Science_](https://www.ncbi.nlm.nih.gov/pubmed/18451266), [Wilhelm _et al. Nature_](https://www.ncbi.nlm.nih.gov/pubmed/18488015), [Mortazavi _et al. Nature Methods_](https://www.ncbi.nlm.nih.gov/pubmed/18516045), [Lister _et al. Cell_](https://www.ncbi.nlm.nih.gov/pubmed/18423832), [Cloonan _et al. Nature Methods_](https://www.ncbi.nlm.nih.gov/pubmed/18516046), [Marioni _et al. Genome Res._](https://www.ncbi.nlm.nih.gov/pubmed/18550803), [Morin _et al. Biotechniques_](https://www.ncbi.nlm.nih.gov/pubmed/18611170)) marked the start of a new technology: RNA-seq, a method that can profile the whole transcriptome of a sample. Let's look at the Mortazavi et al. paper published in __Nature Methods__. Go to the journal page of the paper by clicking [here](https://www.nature.com/articles/nmeth.1226). Scroll down to the __"Supplementary Information"__ section, and donwload the __"Supplementary Dataset 1"__, which is a tab-delimited file that you can open with Excel (be careful NOT to save in Excel, though!) or whatever suitable programs you like. Look at the 6th column named __'finalRPKM'__. This column contains the values of the expression of all the genes in the human genome in that specific sample. __Can you plot the distribution of those values using a graph or table we introduced during the lecture? What are the smallest/largest values, the median and the lower/upper quartile? Do you see any patterns in the graph or table you just created?__
2. I have compiled some information of all annotated human genes from the [Ensembl database](https://ensembl.org) (__time stamp: 2022-02-14T16:59:00+08:00__). You can donwload the zipped file from [here](/src/grch38_ensembl_gene_105.txt.gz). If you unzip it, you will find a tab-delimited file again. Each row describes a gene, and the meaning of each column is indicated in the header (the first row). Scientists have categorised all genes into different types (the 3rd column). __Can you figure out how many types of genes are there? How many genes are there in each type?__ Here we only care about all the __"protein_coding"__ genes. The length of those protein_coding genes can be simply computed by Gene end (bp) - Gene start (bp) + 1. Once you computed the lengths of all genes, look at the first digit of those numbers. Of course, the first digit can only be 1 - 9. __Can you created a frequency table or bar chart to show the absolute frequency of each digit?__


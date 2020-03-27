![Datasaur](figures/DinoSequentialSmaller.gif)
#TOC
# Overview & Motivation:
 Why do we visualise raw data? Raw data is lame! where's that cool association? let me see the stats!
 We visualise our raw data to:
  - Make sure that all assumptions of our planned tests are met.
  - Catch errors that have escaped initial quality control.
  - Spot patterns that would be hidden by advanced statistics.

#Task1
Visualise the galton height data.
 - load the data
 - plot overall distribution/histogram (hist, kde?)
 - plot box & whisker by gender
 - plot scatter with individual, mean parent height
#Task2

#Task3

#Task4

#Task5

Visualise phenotypes and calculate heritability
Time: 13:15-16:00, 2h45m
Tools: R, plink2

Learning outcomes:
The students will familiarise themselves with a few different ways of visualising phenotypes, mainly scatter, box & whisker plots and histograms.
The students will get a decent understanding of how a polygenic architecture will influence the phenotype distribution.
The students will get a vague idea of why the normalisation of some data is necessary, and how to go about it.
The students will get a deeper understanding of what heritability is.
The students will learn how to build a kinship matrix from pedigree data, as well as estimate one from genomic data using plink2
The students will learn how to estimate heritability from kinship+phenotype data using REML methods built into plink2

Tasks:
Phenotypes:
Visualise different phenotypes. What kind of genetic architecture?
Maybe have them run some basic simulations first for n biallelic genes with 1/n and  -1/n effect size and  ( I have them in python, need to translate them to R), and get a feeling for phenotype distributions in form of histograms.
Look at two different “real-world” phenotypes and guess what the genetic architecture could be ( e.g. Galton height data & something that’s vaguely monogenic.)
Normalisation of phenotypic data. Why and how.
Heritability:
Vague overview -> galton height data for basic understanding -> scatter with some colorations for f/m
Kinship matrix -> how is it made?
From family data -> explanation, but then readymade from galton data
Estimated from genomic data -> plink2, using chicken data, compare with pedigree
Using kinship matrices with plink2/REML to estimate heritability

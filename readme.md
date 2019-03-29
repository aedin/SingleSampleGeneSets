---
title: "Workshop_ssGSA"
output: html_document
---
# Single Sample Gene Set Analysis 

# Instructor(s) name(s) and contact information

Aedin Culhane aedin at jimmy.harvard.edu

# Workshop Description
Single sample gene set analysis is widely used to discover new molecular subtype or clusters in molecular profiles of biological samples. For example Single sample gene set analysis was used to refine ovarian cancer molecular subtypes (Verhaak et al., 2013) and define cancer immune subtypes (Tamborero et al., 2018, Thorsson et al., 2018). 

This hands-on workshop will compare different approaches for extracting single samples gene set scores and 1) how these scores can be used to discover subtypes in samples and 2) discover new genes or proteins that might associated with a biological trait of interest 

## Pre-requisites

List any workshop prerequisites, for example:

* Basic knowledge of R syntax
* Familiarity with the Prinipcal component analysis and Gene Ontology

If you are unfamiliar with Prinipcal component analysis, please review the following references before the workshop
* Chapter 7 of Huber and Holmes book Modern Statistics for Modern Biology  http://web.stanford.edu/class/bios221/book/Chap-Multivariate.html
* Stein-O’Brien et al. , 2018  Enter the Matrix: Factorization Uncovers Knowledge from Omics DOI:https://doi.org/10.1016/j.tig.2018.07.003
* Meng et al,. 2016. Dimension reduction techniques for the integrative analysis of multi-omics data     https://academic.oup.com/bib/article/17/4/628/2240645

## Workshop Participation

This will be instructor led and hands-on.  We will lead students through several examples and explain the pros and cons of methods for each analysis question

## _R_ / _Bioconductor_ packages used

-GSVA :ssGSEA single sample gene set analysis (ssGSEA), 
-GSVA:gvsa gene set variation analysis (gsva) 
-moGSA: multi omics integrative gene set analysis

We will also compare these approaches to  

-EGSEA: ensemble gene set analysis
-fgsea: fast gene set analysis

Canoical correlation analysis (mixOmics, RGCCA) and the recently described Argelaguet et al., approach MOFA (http://msb.embopress.org/content/14/6/e8124)

## Time outline

A 45-minute workshop:

| Activity                                               | Time |
|--------------------------------------------------------|------|
| Background/Introduction to ssGSEA, GSVA                | 10m  |
| Gene set databases (GO,MSigDB,Graphite,Target)         | 5m   |
| Introduction to ssGSA                                  | 10m  |
| Application/Comparisons of different methods           | 15m  |
| Questions                                              | 5m   |

# Workshop goals and objectives


## Learning goals

* Describe how to run different ssGSA methods
* identify pros/cons for each approach for cluster discovery
* Become familiar with differnt gene set database 


## Learning objectives

* use GSVA to generate ssGSEA and ssGSVA scores of genesets
* use moGSA to generate gene set scores using matrix factorization (of a single and multiple datasets)
* Recognise when is can be applied and when other approaches do better
* Understand why weighting of datasets in multi-omics factor analysis is important
* Understand the difference between approaches that maximize the correlation or covariance between eigenvectors
* Understand how difference matrix factorization methods score genesets (MOFA, moGSA, pathwayPCA).
* Learn which databases contain gene sets of interest (for RNAseq, proteins or single cell analysis)


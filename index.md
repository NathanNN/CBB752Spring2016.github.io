---
layout: page
title: CBB752Spring2016 Final Project
---

About the Course
----------------

-   **Title:** Bioinformatics: Practical Application of Data Mining & Simulation

-   **Instructor:** [Gerstein, Mark](<http://www.gersteinlab.org>)

-   **Introduction:** Bioinformatics encompasses the analysis of gene sequences,
    macromolecular structures, and functional genomics data on a large scale. It
    represents a major practical application for modern techniques in data
    mining and simulation. Specific topics to be covered include sequence
    alignment, large-scale processing, next-generation sequencing data,
    comparative genomics, phylogenetics, biological database design, geometric
    analysis of protein structure, molecular-dynamics simulation, biological
    networks, normalization of microarray data, mining of functional genomics
    data sets, and machine-learning approaches to data integration.

-   Check out our [awsome course website](<http://cbb752b16.gersteinlab.org>).

-   Check out [this awsome post of related bioinformatics
    topics](<%7B%%20post_url%202016-4-10-Categories-of-knowledge-for-bioinformatics-education%20%%7D>).

About the Final Project
-----------------------

-   **Why:** Instead of generating papers or codes that nobody would ever read
    (expect for the TAs), we want to encourage the innovative generation of
    products that could potentially benefit the bioinformatics community.

-   **When:** Released at April 14th, and will be due at 11:59pm May 5th.

-   **How:** Each student will coorporate with classmates to work on three (or
    four for extra credits) different projects. The generated codes and
    documents will be published on this website to be resources for later
    students and researches.

-   **What:** Project topics are as following. Students can choose three to four
    favorite projects to work on.

### For all sub-projects, your group will have to provide

1.  R card: sample input, source code in R, sample output, and documentation on
    how to execute your code

2.  Python card: sample input, source code in Python, sample output, and
    documentation on how to execute your code

3.  English card: methodology and background introduction

### Available Topics

#### 1. QC steps

1.1 Propose a tool that removes barcode or sequence identifier from FastQ file.

1.2 Propose a tool that generates “quality control statistics” from FastQ file.

1.3 Propose a tool that trims reads based on quality score from FastQ filee.

#### 2. Sequence Analysis

2.1 Propose a tool that generates pileup format from SAM file.

2.2 Propose a tool that calculates FPKM (or TPM, and justify your choice) from
given SAM and GTF files.

2.3 Propose a tool that calculates intersection between two BED files.

2.4 Propose a tool that calls SNVs from pileup file.

2.5 Propose a tool that calculates differentially expressed genes from gene
expression file (decide your own format)

2.6 Propose a tool that finds k-mer motif enrichment from a given nucleotide
sequence.

#### 3. Network Analysis

3.1 Propose a tool that calculates co-expressed gene network from gene
expression file (decide your own format)

3.2 Propose a tool that calculate their degree centrality and betweenness
centrality from PPI file. PPI data can be downloaded from DIP, BIND, MIPS, MINT,
and InAct databases.

3.3 Propose a tool that calculates enrichment level of gene expression data
given pre-defined gene sets
([http://software.broadinstitute.org/gsea/msigdb](<https://urldefense.proofpoint.com/v2/url?u=http-3A__software.broadinstitute.org_gsea_msigdb&d=AwMFaQ&c=-dg2m7zWuuDZ0MUcV7Sdqw&r=PnTFVO2L44pkkv9ojQ0IMDygcpAI3ijI-U1aZXdN85Y&m=0qYw2y8MqbEaBguyXvxmBwvTb67SzblG5ILDT9kuscI&s=ah6gw5_TiY43zaFez-Xxusu-JRdMKObrVsokKQOUCyw&e=>)).

#### 4. Protein Analysis

4.1 Propose a tool that generate 6-frame translation from a nucleotide sequence.
Since DNA is interpreted in groups of three nucleotides (codons), a DNA strand
has three distinct reading frames. 

4.2 Propose a tool that back-translate protein sequence to nucleotide sequences.
There will be ambiguous DNA sequences and you will have to propose a format of
output to summarize results.

4.3 Propose a tool that calculate distance between two alpha carbons from a PDB
file. (The program should output a distance between two atoms in angstroms)
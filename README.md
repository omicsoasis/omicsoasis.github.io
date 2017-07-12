<!-- This file provides the CONTENT for the OASIS website -->
<!-- javascript links are at the bottom of this file to improve page loading -->

<div class="toc-wrapper">
  <ol class="toc js-toc"></ol>
</div>

<p><a id="home" title="OASIS Introduction" class="toc-item"></a></p>

# OASIS by Jim Perry

[**HOME**](/) &nbsp; &nbsp; [**Latest Release**](https://github.com/omicsOASIS/OASIS-releases-issues-Q-and-A/releases/latest){:target="_blank"} &nbsp; &nbsp; [**Issues and Q&A**](https://github.com/omicsOASIS/OASIS-releases-issues-Q-and-A/issues){:target="_blank"} &nbsp; &nbsp; [**MMAP Cheat Sheet**](/CHEATSHEET.html)

## OASIS: Omics Analysis Search and Information System

MMAP is a comprehensive mixed model program for analysis of pedigree and population data. It provides an optimized and flexible platform that incorporates a wide range of covariance structures such as additive, dominance, epistasis, maternal and imprinting using pedigree and/or genotype data and also allows users to define their own covariance structures. Likelihood calculations use multi-threaded optimized matrix libraries to handle multiple random effects. MMAP can import data from a variety of imputation programs to avoid data manipulation and IBS/IBD programs to build covariance structures.

MMAP uses a fast low-memory method to calculate additive and dominant genetic covariance structures using SNP data, which can be quite challenging for large data sets. For polygenic SNP analysis MMAP can store SNP-covariance products to reduce the complexity subsequent analyses with the same subjects to linear regression, independent of phenotype or covariates.

<p><a id="installation" title="Installation" class="toc-item"></a></p>

### Installation

MMAP is compiled with the Intel Math Kernel library for the Unix/Linux environment and uses BLAS and LAPACK libraries. To ensure compatibility only a static executable is currently available. After download, be sure to make the file executable. [Click here to download OASIS](https://github.com/omicsOASIS/OASIS-releases-issues-Q-and-A/releases/latest){:target="_blank"}.


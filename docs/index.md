---
layout: default
---

# Overview of HoneyBADGER

`HoneyBADGER` (**h**idden Markov model integrated **B**ayesian **a**pproach for **d**etecting CNVs and LOHs from sin**g**le-c**e**ll **R**NA-seq data) identifies and infers the presence of subclone-specific CNV and LOH events in individual cells and reconstruct subclonal architecture using scRNA-seq data. 

The overall approach to the differential expression analysis is detailed in the following publication:
COMING SOON!

## Sample analysis and images

### iterative HMM approach for CNV detection
![]({{ site.baseurl }}/assets/img/approach.jpg)

### Bayesian model to infer CNVs in single cells using allele and expression data
![]({{ site.baseurl }}/assets/img/allele.jpg)  
![]({{ site.baseurl }}/assets/img/expression.jpg)

## Installation

To install `HoneyBADGER`, we recommend using `devtools`:

```
require(devtools)
devtools::install_github('JEFworks/HoneyBADGER')
```

## Tutorials
- [Getting Started](Getting_Started.md)

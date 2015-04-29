# salvo
Salmonella MLVA typing from short read sequences

## Authors

Torsten Seemann and Dieter Bulach

## Introduction

The MLVA is a measure of the number of specific tandem repeats present at five loci, four of which
are located on the chromosome and one on a plasmid. The current laboratory test uses a PCR­based 
method; primers specific to each of the loci are used to amplify each of the tandemly repeated regions 
and a small section of the flanking region. A simple calculation is used for four of the loci to determine 
the number of copies of the tandem repeat at each locus. For one locus (STTR3), where there is a 
combination of 27 and 33 base tandem repeat units, the number of repeat units cannot be derived 
from the size of the amplicon and so the size (in bp) is reported and not the number of repeats. The 
listing of the result for each locus, each separated by a “­“ is the MLVA profile. 

Looking at the range of 
the numbers of repeats observed at each locus from a large set of isolates, 29 six­base tandem 
repeats appears to be the maximum length/size for the total repeat unit for STTR9, STTR5, STTR6, 
and STTR10pl. This is a repeat span of 174 bases – this repeat span can be traversed by MiSeq 
reads and thus a ‘genomics based’ determination of four of the five loci is possible. The STTR3 repeat 
unit will not be traversed and therefore not tractable to this read spanning approach (nor a read­pair 
approach as library ‘insert’ size varies – no way to determine the size or the sequence of the all the 
tandem repeat region).

## VNTR locii

Locus | Flanking Length | Amplicon length | Repeat length | Repeat No | Code | Variability
------|-----------------|-----------------|---------------|-----------|------|------------
STTR9 | 144 | 162 | 9 | 2 | 3 | Low
STTR5 | 175 | 247 | 6 | 12 | 13 | Medium
STTR6 | 264 | 318 | 6 | 9 | 10 | High
STTR10pl | 311 | 377 | 6 | 11 | 12 | High
STTR3 | 106 | 523 | 27/33 | 2+11 | 523 | Low

## References

* [Analysis of Salmonella enterica serovar Typhimurium variable-number tandem-repeat data for public health investigation based on measured mutation rates and whole-genome sequence comparisons.](http://www.ncbi.nlm.nih.gov/pubmed/24957617)
* [Using MLVA to type strains of Salmonella Typhimurium in New South Wales](http://www.ncbi.nlm.nih.gov/pubmed/18361866)

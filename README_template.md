# README_template

# Description: CITE-seq of HSPC and Mature bone marrow mononuclear cells in Scl-Cre SRSF2 P95H mutant vs WT mice

2023_06_23

## Summary

This project seeks to understand how ... using the model \... for the purpose of ...

## Contributors

Name, role...

# Sample prep

### Basic Info

| Category                 | Info               |
|--------------------------|--------------------|
| Organism                 | Black 6 mouse      |
| Tissue                   | Bone Marrow        |
| Genetic Modification     | Scl-Cre SRSF2 P95H |
| Sex                      | Female             |
| Molecule                 | Total RNA          |
| Single or paired-end     | paired             |
| Instrument model         | NovaSeq            |
| Targeted cells / channel | 20K                |
| Expected read length     | 150                |

### Subjects

| Subject ID | Genotype |
|------------|----------|
| 1880       | WT       |
| 1881       | WT       |
| 1982       | P95H mut |
| 1983       | P95H mut |

### Cells

FACS sorted Bone marrow populations:

1.  HSPC: DAPI (-), mCD45 (+), cKit(CD117) (+), tdTomato (+)
2.  Mature: DAPI (-), Ter119 (-), mCD45 (+), tdTomato (+)

### CITE ADTs

[CD4, CD8a, Ly-6C, CD11b, Ly-6G, CD44, CD19, CD135, CD16/32, Sca1, CD201, B220, CD115, CD11c, CD62L, F4/80, I-A/I-E, CD127, CD150, CD48, NK1.1, CD3, CD27, CCR2, CX3CR1, CD41, CD34]

### Hashing

| Subject ID | Compartment | Hash |
|------------|-------------|------|
| 1880       | HSPC        | 1    |
| 1881       | HSPC        | 2    |
| 1982       | HSPC        | 3    |
| 1983       | HSPC        | 4    |
| 1880       | Mature      | 5    |
| 1881       | Mature      | 6    |
| 1982       | Mature      | 7    |
| 1983       | Mature      | 8    |

### Library prep

Notes: Samples were pooled after hashing, then run on two separate channels in the 10X controller.

Protocol: Chromium Next GEM Single Cell 3' Reagent Kits, Dual Index (v3.1 Chemistry)

Kit(CAT):

1.  Chromium Next GEM Single Cell 3' Kit v3.1, 4 rxns (PN-1000269)
2.  3' Feature Barcode Kit (PN-1000262)
3.  Dual Index Kit TT Set A (PN-1000215)
4.  Dual Index Kit NT Set A (PN-1000242)
5.  Chromium Next GEM Chip G Single Cell Kit, 16 rxns (PN-1000127)

### Libraries

Sample naming convention: compartment_subjectID_genotype_10Xchannel

| Library Name       |
|--------------------|
| HSPC_1880_WT_1     |
| HSPC_1881_WT_1     |
| HSPC_1982_P95H_1   |
| HSPC_1983_P95H_1   |
| Mature_1880_WT_1   |
| Mature_1881_WT_1   |
| Mature_1982_P95H_1 |
| Mature_1983_P95H_1 |
| HSPC_1880_WT_2     |
| HSPC_1881_WT_2     |
| HSPC_1982_P95H_2   |
| HSPC_1983_P95H_2   |
| Mature_1880_WT_2   |
| Mature_1881_WT_2   |
| Mature_1982_P95H_2 |
| Mature_1983_P95H_2 |

# Analysis

### Data locations

Raw:

...

Preprocessed (ie. CellRanger):

...

Downstream:

...

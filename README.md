# RNA-Seq-GSE150910-Analysis
RNA-seq functional enrichment analysis using GSE150910 dataset (GO &amp; KEGG)

## Project Overview

This project presents a complete RNA-seq analysis workflow using the GSE150910 dataset. The goal was to identify significantly expressed genes and evaluate their functional relevance using Gene Ontology (GO) and KEGG pathway enrichment analysis. The dataset consists of RNA-sequencing data from lung tissue samples, and the analysis was conducted using Python in a Jupyter Notebook environment.

## Dataset Information

Dataset ID: GSE150910
Data Type: RNA-Seq (gene expression)
Source: NCBI GEO
Samples: Lung tissue samples
Platform: Illumina NovaSeq 6000

## Objectives

* Identify statistically significant genes from RNA-seq data
* Perform functional enrichment analysis
* Visualize enriched GO terms and KEGG pathways
* Interpret results based strictly on statistical outputs

## Methodology

1. Data preprocessing and normalization
2. Identification of significant genes
3. Gene Ontology (GO) enrichment analysis
4. KEGG pathway enrichment analysis
5. Visualization using bar plots (−log10 adjusted p-values)

## Results

* A subset of genes showed statistically significant expression differences
* GO enrichment analysis revealed significant functional groupings
* KEGG pathway analysis identified overrepresented pathways
* Barplots confirmed that gene expression changes are not random but statistically structured

## Tools 

* Python
* Jupyter Notebook
* GSEApy
* Pandas, NumPy
* Matplotlib

## Biological Interpretation 

The biological interpretation is based entirely on the enrichment results and gene lists generated in this analysis.

1. Evidence of Structured Gene Expression

The enrichment analysis demonstrates that the identified significant genes are not randomly distributed. Instead, they are grouped into statistically enriched Gene Ontology categories and KEGG pathways.

This indicates that:
Gene expression changes occur in coordinated patterns
These patterns reflect underlying functional organization

2. Recurrent Genes Across Enriched Terms

Several genes repeatedly appear in the enrichment outputs, including:

CX3CR1
CCL2
CCL11
CCL24
CXCL6
CHRM1, CHRM2, CHRM3
VIPR1
CALCA, CALCRL, RAMP2

The recurrence of these genes across multiple enriched terms suggests:

They contribute significantly to the statistical enrichment
They are central to the observed gene expression patterns
3. GO Enrichment Interpretation

The GO barplot (based on −log10 adjusted p-values) shows that:

Multiple Gene Ontology terms are significantly enriched
The enrichment is statistically robust after correction for multiple testing

This confirms that:

The gene set maps to defined biological categories
The observed patterns are statistically meaningful

4. KEGG Pathway Interpretation

The KEGG pathway analysis shows:
Significant enrichment of pathways
Ranking based on adjusted p-values

This indicates that:

The identified genes are overrepresented in known biological pathways
These pathways represent structured functional groupings of the gene set

5. Overall Interpretation

From the combined GO and KEGG results:

The gene expression changes are not isolated events
They form statistically significant functional clusters
These clusters are consistently supported across:

GO enrichment
KEGG pathway analysis






RNA-seq Analysis of Airway Smooth Muscle Cells (GSE52778)

Exploratory gene expression analysis of a public RNA-seq dataset comparing dexamethasone-treated and untreated human airway smooth muscle cells.

## Dataset
- *Source:* NCBI GEO, accession [GSE52778](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE52778)
- *Data type:* RNA-seq, FPKM-normalized expression matrix
- *Conditions compared:* dexamethasone-treated vs. untreated samples

## Repository Contents
- FPKM expression matrix of all samples
- GSE52778_Top25_Genes.csv: list of the top 25 genes from the analysis

## Key Findings
- The top 25 genes were dominated by small non-coding RNAs (SNORD and MIR families).
- Ferritin genes (FTL, FTH1) and QSOX1 were also among the top genes.

## Limitations
- The data is FPKM-normalized, which favors short transcripts, so small RNAs may appear inflated. This analysis is exploratory; a formal differential expression analysis would need raw counts (e.g., with DESeq2).

## Author
Jannat Alam, BTech Biotechnology

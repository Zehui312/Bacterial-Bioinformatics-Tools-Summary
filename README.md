# 🧫 Bacterial Bioinformatics Tools Summary

A curated collection of bioinformatics tools for **bacterial genomics, microbiome analysis, and transcriptomics**.

---

# 📌 Table of Contents

- [1. Data Downloading](#1-data-downloading)
- [2. Data Processing](#2-data-processing)
- [3. Sequence Processing (QC & Trimming)](#3-sequence-processing-qc--trimming)
- [4. Sequence Alignment](#4-sequence-alignment)
- [5. Assembly](#5-assembly)
- [6. File Utilities](#6-file-utilities)
- [7. Genome Quality & Typing](#7-genome-quality--typing)
- [8. Annotation](#8-annotation)
- [9. Phylogenetics & Pangenome](#9-phylogenetics--pangenome)
- [10. Structural Variation (SV)](#10-structural-variation-sv)
- [11. RNA-seq Analysis](#11-rna-seq-analysis)
- [12. Microbiome Analysis](#12-microbiome-analysis)
- [13. Visualization](#13-visualization)
- [14. Databases](#14-databases)
- [15. Mobile Genetic Elements](#15-mobile-genetic-elements--defense-systems)
---

# 1. Data Downloading

- **NCBI Datasets**  
  👉 Download genome assemblies and metadata  
  🔗 https://www.ncbi.nlm.nih.gov/datasets/docs/v2/reference-docs/command-line/datasets/

- **SRA Toolkit**  
  👉 Download sequencing data from SRA  
  🔗 https://github.com/ncbi/sra-tools

- **Entrez Direct (EDirect)**  
  👉 Query NCBI databases via command line  
  🔗 https://www.ncbi.nlm.nih.gov/books/NBK179288/

---

# 2. Data Processing

- **csvtk**  
  👉 High-performance CSV/TSV processing toolkit  
  🔗 https://github.com/shenwei356/csvtk

---

# 3. Sequence Processing (QC & Trimming)

- **fastp** – QC + trimming  
  🔗 https://github.com/opengene/fastp  

- **MultiQC** – QC report aggregation  
  🔗 https://github.com/MultiQC/MultiQC  

- **cutadapt** – adapter trimming  
  🔗 https://github.com/marcelm/cutadapt  

- **Porechop** – ONT adapter trimming  
  🔗 https://github.com/rrwick/Porechop  

- **seqkit** – FASTA/Q toolkit  
  🔗 https://github.com/shenwei356/seqkit  

- **seqtk** – lightweight sequence processing  
  🔗 https://github.com/lh3/seqtk  

- **sequence-stats** – sequence statistics  
  🔗 https://github.com/raymondkiu/sequence-stats  

- **Dorado** – ONT basecalling & demultiplexing  
  🔗 https://github.com/nanoporetech/dorado  

- **chopper** – long-read filtering  
  🔗 https://github.com/wdecoster/chopper  

- **Filtlong** – high-quality read selection  
  🔗 https://github.com/rrwick/filtlong  

---

# 4. Sequence Alignment

- **Bowtie2** – short-read alignment  
  🔗 https://github.com/BenLangmead/bowtie2  

- **BWA** – standard short-read mapper  
  🔗 https://github.com/lh3/bwa  

- **BWA-MEM2** – faster BWA  
  🔗 https://github.com/bwa-mem2/bwa-mem2  

- **minimap2** – long-read alignment  
  🔗 https://github.com/lh3/minimap2  

- **DIAMOND** – protein alignment  
  🔗 https://github.com/bbuchfink/diamond  

- **MUMmer** – genome alignment  
  🔗 https://github.com/mummer4/mummer  

---

# 5. Assembly

- **Shovill** – bacterial genome assembly  
  🔗 https://github.com/tseemann/shovill  

- **Miniasm** – ultra-fast long-read assembly  
  🔗 https://github.com/lh3/miniasm  

- **Flye** – long-read assembler  
  🔗 https://github.com/mikolmogorov/Flye  

- **Medaka** – ONT polishing  
  🔗 https://github.com/nanoporetech/medaka  

- **Bandage** – assembly graph visualization  
  🔗 https://github.com/rrwick/Bandage  

---

# 6. File Utilities

- **samtools** – BAM processing  
  🔗 https://github.com/samtools/samtools  

- **bcftools** – VCF processing  
  🔗 https://github.com/samtools/bcftools  

---

# 7. Genome Quality & Typing

- **CheckM** – genome quality assessment  
  🔗 https://github.com/ecogenomics/checkm  

- **Mash** – genome distance estimation  
  🔗 https://github.com/marbl/Mash  

- **FastANI** – ANI calculation  
  🔗 https://github.com/ParBLiSS/FastANI  

- **pyani** – ANI toolkit  
  🔗 https://github.com/widdowquinn/pyani  

- **MLST** – strain typing  
  🔗 https://github.com/tseemann/mlst  

---

# 8. Annotation

- **Prokka** – rapid genome annotation  
  🔗 https://github.com/tseemann/prokka  

- **Bakta** – modern annotation tool  
  🔗 https://github.com/oschwengers/bakta  

---

# 9. Phylogenetics & Pangenome

- **Panaroo** – pangenome analysis  
  🔗 https://pangenome.org/  

- **IQ-TREE** – phylogenetic tree inference  
  🔗 https://iqtree.github.io/  

- **Snippy** – SNP calling pipeline  
  🔗 https://github.com/tseemann/snippy  

- **Roary** – pangenome pipeline  
  🔗 https://github.com/sanger-pathogens/Roary  

- **iTOL** – tree visualization  
  🔗 https://itol.embl.de/  

---

# 10. Structural Variation (SV)

- **Sniffles** – long-read SV detection  
  🔗 https://github.com/fritzsedlazeck/sniffles  

- **Miniwalk** – graph-based SV analysis  
  🔗 https://github.com/aleixcanalda/miniwalk  

- **SVIM-asm** – assembly-based SV detection  
  🔗 https://github.com/eldariont/svim-asm  

---

# 11. RNA-seq Analysis

- **featureCounts** – read counting  
  🔗 https://subread.sourceforge.net/  

- **DESeq2** – differential expression  
  🔗 https://github.com/thelovelab/DESeq2  

- **UMI-tools** – UMI processing  
  🔗 https://github.com/CGATOxford/UMI-tools  

- **Seurat** – single-cell analysis  
  🔗 https://satijalab.org/seurat/  

---

# 12. Microbiome Analysis

- **Kraken2** – taxonomic classification  
  🔗 https://github.com/DerrickWood/kraken2/wiki  

- **Centrifuge** – classification with low memory  
  🔗 https://www.ccb.jhu.edu/software/centrifuge/  

- **Kneaddata** – host removal  
  🔗 https://github.com/biobakery/kneaddata  

- **MetaPhlAn** – marker-based profiling  
  🔗 https://github.com/biobakery/metaphlan  

- **HUMAnN** – functional profiling  
  🔗 https://github.com/biobakery/humann  

- **MEGAHIT** – metagenome assembly  
  🔗 https://github.com/voutcn/MEGAHIT  

- **QIIME2** – microbiome platform  
  🔗 https://github.com/qiime2  

- **LEfSe** – biomarker discovery  
  🔗 https://github.com/SegataLab/lefse  

---

# 13. Visualization

- **IGV** – genome browser  
  🔗 https://github.com/igvteam/igv  

- **Circos** – circular genome plots  
  🔗 https://circos.ca/  

- **Cytoscape** – network visualization  
  🔗 https://cytoscape.org/  

- **Pavian** – metagenomics visualization  
  🔗 https://fbreitwieser.shinyapps.io/pavian/  

- **AliTV** – genome comparison  
  🔗 https://alitvteam.github.io/AliTV/d3/AliTV.html  

---

# 14. Databases

- **SILVA** – rRNA database  
  🔗 https://www.arb-silva.de/  

- **EBI Metagenomics** – microbiome datasets  
  🔗 https://www.ebi.ac.uk/metagenomics  


# 15. Mobile Genetic Elements & Defense Systems

- **CRISPRCasFinder** – identification of CRISPR arrays and Cas proteins  
  🔗 https://github.com/dcouvin/CRISPRCasFinder  

- **MacSyFinder** – detection of molecular systems using gene models (CRISPR-Cas, secretion systems, defense systems, etc.)  
  🔗 https://github.com/gem-pasteur/macsyfinder  

- **PhiSpy** – prophage prediction in bacterial genomes  
  🔗 https://github.com/linsalrob/PhiSpy  

---
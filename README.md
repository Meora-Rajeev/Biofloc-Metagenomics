# Biofloc-Metagenomics
The detailed information on bioinformatics tools/pipelines used are summarized in the manuscript entitled “Metagenome sequencing and recovery of 444 metagenome-assembled genomes from the biofloc aquaculture system” 
by Meora Rajeev, Ilsuk Jung, Yeonjung Lim, Suhyun Kim, Ilnam Kang, and Jang-Cheon Cho, in the journal Scientific Data.

The raw metagenome data were processed through BBduk for obtaining high-quality reads.  

Taxonomic classification to high-quality reads was performed using Kraken2.

Metagenome assemblies were obtained using metaSPAdes.

Metagenome binning was performed using metaWRAP.

Redundant bins were removed and high-quality ones were retained using dRep.

Quality of obtained bins was assesses using CheckM2.

Taxonomic classification to final metagenome-assembled genomes (MAGs) set was obtained using GTDB-Tk.  

![image](https://github.com/Meora-Rajeev/Biofloc-Metagenomics/assets/143373266/508599b3-837e-42d1-9888-18db31cd4a61)

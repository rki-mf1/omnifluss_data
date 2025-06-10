## ENA Sample SRR31096286

# Source 
https://www.ebi.ac.uk/ena/browser/view/SRR31096286

# Metadata
Organism:   Influenza A virus
Instrument Platform:    ILLUMINA
Instrument Model:   Illumina MiSeq
Read Count: 1696376
Base Count: 512305552
Center Name:    SUB14810822
Library Layout: PAIRED
Library Strategy:   AMPLICON
Library Source: VIRAL RNA
Library Name:   LACPHL-INF00543
Library Selection:  RANDOM
Isolation Source:   Clinical
Assembly Method:    TheiaCoV (PHB v2.1.0): IRMA v1.1.5
ENA-FIRST-PUBLIC:   2024-10-24
ENA-LAST-UPDATE:    2024-10-24 

# Info
Sum of FASTQ file sizes:    176 MB

# Preprocessing
seqkit sample -p 0.70 -s 479 SRR31096286_1.fastq.gz -o SRR31096286_1.subsampled.fastq.gz
seqkit sample -p 0.70 -s 479 SRR31096286_2.fastq.gz -o SRR31096286_2.subsampled.fastq.gz

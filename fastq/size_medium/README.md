# ENA Sample SRR31096286

## Source 
https://www.ebi.ac.uk/ena/browser/view/SRR31096286

## Metadata
Organism:   Influenza A virus <br>
Instrument Platform:    ILLUMINA <br>
Instrument Model:   Illumina MiSeq <br>
Read Count: 1696376 <br>
Base Count: 512305552 <br>
Center Name:    SUB14810822 <br>
Library Layout: PAIRED <br>
Library Strategy:   AMPLICON <br>
Library Source: VIRAL RNA <br>
Library Name:   LACPHL-INF00543 <br>
Library Selection:  RANDOM <br>
Isolation Source:   Clinical <br>
Assembly Method:    TheiaCoV (PHB v2.1.0): IRMA v1.1.5 <br>
ENA-FIRST-PUBLIC:   2024-10-24 <br>
ENA-LAST-UPDATE:    2024-10-24  <br>

## Info
Sum of FASTQ file sizes:    176 MB

## Preprocessing
seqkit sample -p 0.70 -s 479 SRR31096286_1.fastq.gz -o SRR31096286_1.subsampled.fastq.gz <br>
seqkit sample -p 0.70 -s 479 SRR31096286_2.fastq.gz -o SRR31096286_2.subsampled.fastq.gz <br>

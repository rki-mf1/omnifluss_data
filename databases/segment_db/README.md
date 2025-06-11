# databases/segment_db 

## ena_segment_db.tar.gz 
GZIP compressed database containing a few publically available full-segment assemblies of the Influenza virus from the European Nucleotide Archive (ENA). <br>
The database is indexed with a sparse KMA index. <br>

## Preprocessing
for i in {HA,MP,NA,NP,NS,PA,PB1,PB2}; do kma index -i ${i}.segment.fasta -o ${i}.segment -Sparse; done <br>

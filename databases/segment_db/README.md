# segment_db 

## Info 
This database contains a few publically available full-segment assemblies of the Influenza virus. <br>
The index subdirectory `kmaindex` is what has to be passed to omnifluss as a segment database. <br>
The index is a sparse KMA index. <br>

## Preprocessing
cd kmaindex <br>
for i in {HA,MP,NA,NP,NS,PA,PB1,PB2}; do ln -s ../${i}.segment.fasta ${i}.segment.fasta; done <br>
for i in {HA,MP,NA,NP,NS,PA,PB1,PB2}; do kma index -i ../${i}.segment.fasta -o ${i}.segment -Sparse; done <br>

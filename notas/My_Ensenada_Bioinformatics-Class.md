# My Ensenada Bioinformatics Class
## UABCS

This page was created from the GitHub of Steven Roberts by César



---



I´am working in the search of Microsatellites on Transcriptome of Pacific Lion´s Paw Scallop. The Transcriptome has not been publish yet. I´am sharing one of the fisrt genome works in this specie.



This is the NCBI register

</Users/Cesar/Desktop/cesar2-btea-nb/imagenes/Myostatina_Ns_gene.png/ width = 50%>

________

###Blasting against Microsatellite of NCBI vs My Micros

This was my code 

```
!blastn \
-outfmt 6 \
-evalue 1E-20 \
-task blastn \
-query ../Big-data/blast/query/MsNsnoprimers.fasta \
-db ../Big-data/blast/db/Ns_Ms_NBCI \
-out ../Big-data/blast/out/MsNs_blastx_NCBI-fmt6.out```

When I run that I found 13 MATCH!!

Here is the top hit for Blast
```
c12765_g1_i1_1	gi |238915582| gb|FJ986365.1|	96.12	103	0	4	1	100	102	1	2e-43	165

```


Now I have to learn how to do annotations for looking for use the micros with important annotation.


One picture of N. subnodosus

</Users/Cesar/Desktop/cesar2-btea-nb/imagenes/Nodipecten.png/ width = 50%>

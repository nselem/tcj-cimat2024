# Sesión 4 Bases de datos (30 min) 

## Introducción
Las bases de datos pueden ser públicas o privadas, acumulan información de los organismos y usualmente tienen algún paquete de análisis asociado a ellas. 

### Ejemplo 1 
[Clavigenomics](https://nselem.github.io/clavigenomics/) una base de datos de Clavibacter michiganensis Bacteria patógena de tomate.  

## Otros ejemplos  
### [NCBI](https://www.ncbi.nlm.nih.gov/)  
NCBI es una de las grandes bases de datos biológicas. Hay información de genes, genomas proteínas, etc de muchos organismos.  
![Streptomyces](strepto.png)   

Esta secuencia del gen de 16s de _Streptomyces lividans_ proviene de NCBI  
>LC026160.1 Streptomyces lividans gene for 16S ribosomal RNA, partial sequence, strain: AS2
GGGGAGCTCTGCAGTCGACGATGACCACTTCGGTGGGGATTAGTGGCGAACGGGTGAGTAACACGTGGGC
AATCTGCCCTGCACTCTGGGACAAGCCCTGGAAACGGGGTCTAATACCGGATACTGACCCTCGCAGGCAT
CTGCGAGGTTCGAAAGCTCCGGCGGTGCAGGATGAGCCCGCGGCCTATCAGCTTGTTGGTGAGGTAATGG
CTCACCAAGGCGACGACGGGTAGCCGGCCTGAGAGGGCGACCGGCCACACTGGGACTGAGACACGGCCCA
GACTCCTACGGGAGGCAGCAGTGGGGAATATTGCACAATGGGCGAAAGCCTGATGCAGCGACGCCGCGTG
AGGGATGACGGCCTTCGGGTTGTAAACCTCTTTCAGCAGGGAAGAAGCGAAAGTGACGGTACCTGCAGAA
GAAGCGCCGGCTAACTACGTGCCAGCAGCCGCGGTAATACGTAGGGCGCAAGCGTTGTCCGGAATTATTG
GGCGTAAAGAGCTCGTAGGCGGCTTGTCGCGTCGGTTGTGAAAGCCCGGGGCTTAACCCCGGGTCTGCAG
TCGATACGGGCAGGCTAGAGTTCGGTAGGGGAGATCGGAATTCCTGGTGTAGCGGTGAAATGCGCAGATA
TCAGGAGGAACACCGGTGGCGAAGGCGGATCTCTGGGCCGATACTGACGCTGAGGAGCGAAAGCGTGGGG
AGCGAACAGGATTAGATACCCTGGTAGTCCACGCCGTAAACGGTGGGCACTAGGTGTGGGCAACATTCCA
CGTTGTCCGTGCCGCAGCTAACGCATTAAGTGCCCCGCCTGGGGAGTACGGCCGCAAGGCTAAAACTCAA
AGGAATTGACGGGGGCCCGCACAAGCGGCGGAGCATGTGGCTTAATTCGACGCAACGCGAAGAACCTTAC
CAAGGCTTGACATACACCGGAAAGCATCAGAGATGGTGCCCCCCTTGTGGTCGGTGTACAGGTGGTGCAT
GGCTGTCGTCAACTCGTGTCGTGAGATGTTGGGTTAAGTCCCGCAACGAGCGCAACCCTTGTCCCGTGGT
GGCCACCAGGCCCTTGGGGTGCTGGGGAACTCACGGGAAAACCGCCGGGGTCAAATCCGAAGGAAAGTGG
GGGACGACGTCAAAGTCTTCATTGCCCCTTATGGTCTTGGGCTGGCCACCGTGGCTACAAATGGCCCGGT
ACAAATGAACTTGCGATACCCGCCAGGGTGGAAGCGAAACCTCAAAAAGCCCGGTTCCAATTCCNGAATG
GGGGGCTTCGAACCTCACCCCCCTGGAAAGTCCGAGATCCCCTAGGAATCCGGAAATACCCATTTTGCGC
GGGGTAAAACATTTTCCCGCGGCCTTTTTTACACACGCCGCCCTTAAACTCTCAAGAAATTCTTGTACAC
CCCCCAGGAACCGGGTGGCCCCCACCCTCTTTTGGGGGAAGGGACTGTTCCCAAAGGTGGGGTTCCCGGC
ACTGGGGGGGGAATNGTTTTCCTCAAGAAGGTAA

#### Ejercicio 1    
Busca la taxonomía completa de _Streptomyces coelicolor_ en [NCBI taxonomy]([url](https://www.ncbi.nlm.nih.gov/taxonomy)).  

#### Ejercicio 2 
Utiliza [blastn]([url](https://blast.ncbi.nlm.nih.gov/Blast.cgi?PROGRAM=blastn&BLAST_SPEC=GeoBlast&PAGE_TYPE=BlastSearch)) para buscar como query el 16S de _Streptomyces lividans_ 
contra toda la base de NCBI

### [Ábrol de la vida](http://tolweb.org/tree/)
En el árbol de la vida podrás explorar la diversidad de la vida.  

### [RAST](http://rast.nmpdr.org/rast.cgi)  
RAST es un anotador automático. Encuentra genes codificantes y les asigna función.  
Anota en RAST Streptomyces coelicolor y tu organismo ensamblado  
Compáralos  

### [MIBiG](https://mibig.secondarymetabolites.org)    
![antibioticos](antibioticos.png)  
Obten la secuencia de un gen que pertenezca a un cluster de antibióticos y anótala en el documento colaborativo  

### [antiSMASH](https://antismash.secondarymetabolites.org/#!/start)
Anota rápidamente los genomas de Streptomyces y de tu ensamblado. ¿Qué diferencias ves? Anóta tu conclusión en el documento colaborativo.  

### [Kegg](https://www.genome.jp/kegg/),[Brenda](https://www.brenda-enzymes.org/), [pfam](https://pfam.xfam.org/)     
Busca HisA en ambas bases ¿Qué obtienes? 
Toma la secuencia de HisA y analízala en pFAM, qué obtienes? 

¿Cómo son tus organismos en RAST?  

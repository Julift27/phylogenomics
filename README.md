# Phylogenomics

Durante la clase de filogenómica lo que hicimos fue construir la filogenia de algunas especies de vertebrados desde un enfoque coalescente y concatenado. Lo primero que realizamos fue encontrar regiones ortólogas entre las proteínas de las especies evaluadas para obtener las secuencias de los "Orthogroups", los cuáles nos agrupan los genes ortologos. Debido a que los datos de secuenciación pueden tener varios errores se hizo un filtraje de calidad de las secuencias. Después de esto realizamos un alineamiento múltiple con el fin de poder identificar nucleótidos o aminoácidos homólogos y poderlos comparar. A este alineamiento se le removieron las regiones que no se pudieron alinear correctamente, por ejemplo se removieron regiones en donde se encontraban gaps en el 80% de los individuos. Estos alineamientos los concatenamos para poder analizar todos los individuos y las particiones. A partir de esto se realizó un árbol de máxima verosimilitud por particiones y sin particiones. Finalmente, también se hizo un árbol por coalescencia, en el que se obtiene un árbol por cada orthogroup y después se concatenan para obtener el árbol de coalescencia. 

## Partitioned tree
![Caos](https://github.com/Julift27/phylogenomics/blob/af0796f48e6305f00443b2105257f730dc81b743/partitioned.treefile_page-0001.jpg)

## Unpartitioned tree
![Caos](https://github.com/Julift27/phylogenomics/blob/ddf537596f17be1efac7645b769651a732bb04d9/unpartitioned.treefile_page-0001%20(1).jpg)

## Coalescence tree
![Caos](https://github.com/Julift27/phylogenomics/blob/9d42f972428ac71a1e52513463f95dfe55b60c8d/species_tree_ASTRAL.tre_page-0001%20(1).jpg)


Los tres árboles realizados varían por los métodos en los que se realiza el análisis. En el árbol por particiones se hace un análisis de los cambios observados en el genoma por fragmentos, lo que implica que el análisis de los genomas se hace por partes. Por otro lado, el árbol sin particiones realiza un análisis del genoma completo para evaluar los cambios o susticiones que se han generado en las secuencias analizadas. Finalmente, el árbol de coalescencia evalúa las similitudes de las secuencias a partir del punto en el que coalescen las ramas, teniendo en cuenta que estos rasgos deben venir de un ancestro común.

De manera general los árboles con particiones y sin particiones otorgan los mismos clados, con Bootstrap iguales o muy similares en todos los casos. El primer clado formado, en la parte superior, junto con los dos primeros miembros del siguiente clado corresponden a peces. Después se observa otro clado separado en reptiles y aves, del gran taxa reptilia. Como clado hermano al gran taxa reptilia, se forman los mamíferos, en el cuál se encuentra la agrupación de marsupiales. Por fuera de este clado de reptilia se encuentra un individuo perteneciente a los anfibios. Finalmente, como grupo hermano del clado de reptilia, mamíferos y anfibios se encuentran los peces pulmonados, más cercanos a estos grupos que el otro clado de peces.
El árbol de coalescencia otorga relaciones similares. Esto indica que las similitudes entre estas especies también están presentes. Lo que ocurre con este árbol es que se observan los clados “invertidos”, es decir, los clados que se observan en la parte superior de los árboles de máxima verosimilitud se encuentran en la parte inferior del árbol de coalescencia. Además, observamos pequeñas agrupaciones diferentes como el intercambio de Canis lupus y Mus musculus en su relación con Homo sapiens.
De estos árboles se puede concluir que se separan los grandes taxa de vertebrados, diferenciando los grupos que se tienen presentes en la actualidad.

# CURSO PRÁCTICO DE INICIACIÓN AL USO DE LA SUPERCOMPUTACIÓN APLICADO AL ANÁLISIS DE DATOS RNA-SEQ. 7ª EDICIÓN - Universidad de Leon

## Introducción a R, Bioconductor y anotaciones funcionales

**Author:** Pablo Fonseca 

**Date:** 11/07/23-12/07/2023

## Índice
* [Información general](#Información-general)
* [Programas](#Software-y-Programas)
* [Contacto](#Contacto)

## Información general

Este repositorio contiene el material necesario para las prácticas que se realizarán en los módulos: **Introducción a R y Bioconductor** y **Introducción a las anotaciones funcionales**.

### Enlace para los tutoriales de los módulos

**Introducción a R y Bioconductor:** [https://pablobio.github.io/CursoVeranoRNASeq_2023/intro_R_bioconductor.html](https://pablobio.github.io/CursoVeranoRNASeq_2023/intro_R_bioconductor.html)

**Introducción a las anotaciones funcionales:** [https://pablobio.github.io/CursoVeranoRNASeq_2023/intro_anotaciones_funcionales.html](https://pablobio.github.io/CursoVeranoRNASeq_2023/intro_anotaciones_funcionales.html)

### Database

Los datos necesarios para los tutoriales se encuentran en la carpeta denominada database.


## Software y Programas

Para este curso, necesitará tener instaladas en su ordenador las últimas versiones de R y RStudio. Este software puede descargarse a través de los siguientes enlaces:

- **R:** https://cran.irsn.fr/

- **Rstudio:** https://rstudio.com/products/rstudio/download/

Además de R y RStudio, también necesitarás instalar algunos paquetes que serán necesarios para el análisis. La lista de paquetes utilizados en este curso se puede encontrar a continuación. 

```{r global_options, include = FALSE}
install.packages("ggplot2")
install.packages("patchwork")
install.packages("ggrepel")
install.packages("tidyverse")
BiocManager::install("biomaRt")
BiocManager::install("gprofiler2")
```

## Contacto

**Pablo Fonseca**

[![Gmail Badge](https://img.shields.io/badge/-psouf@unileon.es-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:psouf@unileon.es)](mailto:psouf@unileon.es)
[![Google Scholar Badge](https://img.shields.io/badge/Google-Scholar-lightgrey)](https://scholar.google.com/citations?user=1VUm8EIAAAAJ&hl=pt-BR)
[![ResearchGate Badge](https://img.shields.io/badge/Research-Gate-9cf)](https://www.researchgate.net/profile/Pablo_Fonseca2)

<!-- display the social media buttons in your README -->


[![alt text][6.1]][6]


<!-- links to social media icons -->
<!-- no need to change these -->

<!-- icons with padding -->

[6.1]: http://i.imgur.com/0o48UoR.png (github icon with padding)

<!-- icons without padding -->

[6.2]: http://i.imgur.com/9I6NRUm.png (github icon without padding)


<!-- links to your social media accounts -->
<!-- update these accordingly -->

[6]: http://www.github.com/pablobio

<!-- Please don't remove this: Grab your social icons from https://github.com/carlsednaoui/gitsocial -->

**Grupo MEjoraGeneticaAnimal-ULE (MEGA_ULE)**

[![alt text][1.1]][1]

[1.1]: http://i.imgur.com/tXSoThF.png (twitter icon with padding)

[1.2]: http://i.imgur.com/wWzX9uB.png (twitter icon without padding)

[1]: https://twitter.com/MEGA_ULE

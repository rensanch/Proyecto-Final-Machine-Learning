# Proyecto-Final-Machine-Learning
_Este proyecto utiliza un enfoque de Machine Learning, ocupando datos de RNA-seq para predecir si un paciente padece de miocardiopatía isquémica (ICM). El modelo clasifica en dos categorías: enfermo o sano._

## Comenzando 🖥️
### Pre-requisitos 📋
* R version 4.4.2
* R session: R version 4.4.2 (2024-10-31)

Librerías ocupadas:
```
library(DataExplorer)
library(skimr)
library(ggplot2)
library(GGally)
library(tidyverse)
library(tidymodels)
library(corrplot)
library(dplyr) 
library(nnet)
library(yardstick)
library(viridis)
library(vip)
library(recount3)
library(tidyr)
library(GSVA)
library(GSVAdata)
library(msigdbr)
library(SummarizedExperiment)
library(pheatmap)
library(patchwork)
```

### Instalación 🔧
Instalar **GSVA** y **recount3**:
```
install.packages("BiocManager")
BiocManager::install("GSVA")
library(GSVA)

BiocManager::install("recount3")
library(recount3)

```

## Fuente de los datos 📊

Los datos utilizados en este proyecto provienen del conjunto de datos **GSE48166**, disponible en [Gene Expression Omnibus (GEO)](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE48166). Este conjunto de datos contiene perfiles de expresión génica de pacientes con miocardiopatía isquémica (ICM).

## Estructura del proyecto 📁
El proyecto se divide en cuatro partes principales:
1. **Descarga de datos y carga de librerías:**
    * Reducción de dimensionalidad del dataset con GSVA

2. **Selección del conjunto de datos y análisis inicial:**
    * Documentación del conjunto de datos
    * Análisis Exploratorio de Datos
    * Análisis de reducción de dimensionalidad
    * Relevancia biológica

3. **Enfoque de Machine Learning:**
   * Formulación del problema
   * Implementación del modelo
   * Ingeniería de características

4. **Revisión de la Literatura:**
   * Análisis de la literatura primaria
   * Comparación de Métodos

5. **Resultados e Implementación:**
   * Aplicaicón Técnica
   * Análisis de resultados
   * Perspectiva biológica
   * Futuras direcciones de investigación


## Autores ✒️

_Este trabajo fue realizado por:_

* **Renata Sandoval** - *Trabajo Inicial* - [villanuevand](https://github.com/rensanch)
* **Victoria Lelis** - *Trabajo Inicial* - [VictoriaLelis](https://github.com/VictoriaLelis)

También puedes mirar la lista de todos los [contribuyentes](https://github.com/your/project/contributors) quíenes han participado en este proyecto. 




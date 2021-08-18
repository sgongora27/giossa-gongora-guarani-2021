# Construcción de Recursos para Traducción automática Guaraní-Español

Este repositorio contiene el trabajo desarrollado para el Proyecto de Grado "Expansión de Corpus para Traducción automática Guaraní-Español". Varios de estos recursos fueron presentados en el artículo [``Experiments on a Guarani Corpus of News and Social Media``](https://aclanthology.org/2021.americasnlp-1.16/).

Contenidos:
- Dentro de ``Tests`` se encuentran tests intrínsecos para el guaraní
    - ``capital-common-countries_gn`` y ``family_gn`` son tests de **analogías**.
    - ``MC30_gn`` es un test de **similaridad**.
- Dentro de ``ParallelSet`` se encuentran dos versiones del conjunto paralelo de noticias construido durante el proyecto.
- Dentro de ``Tweets`` se encuentran tres versiones del conjunto de tweets construido durante el proyecto.
- Dentro de ``WordEmbeddings`` se encuentran algunos modelos entrenados con Word2Vec, utilizando el algoritmo *c-bow*.
- Dentro de ``MachineTranslation``se encuentran dos modelos entrenados usando OpenNMT. Uno traduce desde el guaraní al español y otro en sentido opuesto.
- ``gn_frequent_words.csv`` es una lista de palabras frecuentes de guaraní curada manualmente. La revisión se hizo hasta aquellas de frecuencia 10.

Autores: 
- [Nicolás Giossa](https://github.com/giossa94)
- [Santiago Góngora](https://sites.google.com/view/sgongora/)

Tutor: [Luis Chiruzzo](https://scholar.google.com/citations?user=C7c4uCsAAAAJ)

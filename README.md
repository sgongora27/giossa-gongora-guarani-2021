# Construcción de Recursos para Traducción automática Guaraní-Español

Este repositorio contiene el trabajo desarrollado para el Proyecto de Grado [``Construcción de Recursos para Traducción automática Guaraní-Español``](https://www.colibri.udelar.edu.uy/jspui/handle/20.500.12008/30019). Varios de estos recursos fueron presentados en el artículo [``Experiments on a Guarani Corpus of News and Social Media``](https://aclanthology.org/2021.americasnlp-1.16/) y [``Can We Use Word Embeddings for Enhancing Guarani-Spanish Machine Translation?``](https://aclanthology.org/2022.computel-1.16/).

Contenidos:
- Dentro de ``Tests`` se encuentran tests intrínsecos para el guaraní
    - ``capital-common-countries_gn`` y ``family_gn`` son tests de **analogías**.
    - ``MC30_gn`` es un test de **similaridad**.
- Dentro de ``ParallelSet`` se encuentran dos versiones del conjunto paralelo de noticias construido durante el proyecto.
- Dentro de ``Tweets`` se encuentran tres versiones del conjunto de tweets construido durante el proyecto.
- Dentro de ``WordEmbeddings`` se encuentran algunos modelos entrenados con Word2Vec, utilizando el algoritmo *c-bow*.
- Dentro de ``MachineTranslation``se encuentran dos modelos entrenados usando OpenNMT. Uno traduce desde el guaraní al español y otro en sentido opuesto.
- ``gn_frequent_words.csv`` es una lista de palabras frecuentes de guaraní curada manualmente. La revisión se hizo solamente para aquellas de frecuencia 10 o superior.

Autores: 
- [Nicolás Giossa](https://github.com/giossa94)
- [Santiago Góngora](https://sites.google.com/view/sgongora/)

Tutor: [Luis Chiruzzo](https://scholar.google.com/citations?user=C7c4uCsAAAAJ)

## Citation

If you use some of these resources, please cite:


```
@inproceedings{gongora-etal-2021-experiments,
    title = "Experiments on a {G}uarani Corpus of News and Social Media",
    author = "G{\'o}ngora, Santiago  and
      Giossa, Nicol{\'a}s  and
      Chiruzzo, Luis",
    booktitle = "Proceedings of the First Workshop on Natural Language Processing for Indigenous Languages of the Americas",
    month = jun,
    year = "2021",
    address = "Online",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2021.americasnlp-1.16",
    doi = "10.18653/v1/2021.americasnlp-1.16",
    pages = "153--158",
}
```
or

```
@inproceedings{gongora-etal-2022-use,
    title = "Can We Use Word Embeddings for Enhancing {G}uarani-{S}panish Machine Translation?",
    author = "G{\'o}ngora, Santiago  and
      Giossa, Nicol{\'a}s  and
      Chiruzzo, Luis",
    booktitle = "Proceedings of the Fifth Workshop on the Use of Computational Methods in the Study of Endangered Languages",
    month = may,
    year = "2022",
    address = "Dublin, Ireland",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2022.computel-1.16",
    doi = "10.18653/v1/2022.computel-1.16",
    pages = "127--132",
}

```


# Expansión de Corpus para Traducción automática Guaraní-Español
## Modelos de traducción

En este directorio se encuentran dos modelos de traducción que tuvieron buen desempeño en las evaluaciones realizadas.

- **Gn-Es+Vectores13**: entrenado durante 65000 *steps* sobre texto paralelo de noticias.
- **Es-Gn+Vectores13**: entrenado durante 25000 *steps* sobre texto paralelo de noticias.

Ambos modelos fueron entrenados usando el *framework* [OpenNMT](https://opennmt.net/) y toman como *word embeddings* preentrenados a la colección ``Vectores13`` para el guaraní, y la construida por [Azzinnari y Martínez (2016)](https://www.fing.edu.uy/inco/grupos/pln/prygrado/informe_rep_palabras.pdf) para el español.

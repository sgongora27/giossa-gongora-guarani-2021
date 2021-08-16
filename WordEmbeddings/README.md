# Expansión de Corpus para Traducción automática Guaraní-Español
## Colecciones de vectores de palabras

En este directorio se encuentran tres colecciones de vectores de palabras que tuvieron buen desempeño en las evaluaciones realizadas.

- **Vectores09**: de dimensión 150, entrenada sobre la Wikipedia, texto de noticias, la Biblia católica y el Libro de Mormón.
- **Vectores13**: de dimensión 300, entrenada sobre la Wikipedia, texto de noticias, la Biblia católica y el Libro de Mormón.
- **Vectores19**: de dimensión 300, entrenada sobre la Wikipedia, texto de noticias, la Biblia católica, el Libro de Mormón y alrededor de 7000 tweets.

Todas ellas fueron entrenadas usando la implementación de Word2Vec (c-bow) disponible en la biblioteca [Gensim](https://radimrehurek.com/gensim/models/word2vec.html).

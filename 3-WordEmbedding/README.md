# Natural Language Processing

## Custom embedddings con Gensim

![custom_embeddings](https://github.com/tmonreal/Natural_Language_Processing/assets/84754265/a4fcde6c-17dc-4f3d-a9ac-a8655c4c33e3)

En este notebook se utilizará Gensim para crear embeddings customizados basado en un corpus extraido de los tres volúmenes del libro 
"*General Anatomy applied to physiology and medicine*" de Xavier Bichat, los cuáles se obtienen en la página de [Project Gutenberg](https://www.gutenberg.org/ebooks/search/?query=GENERAL+ANATOMY+APPLIED+TO+PHYSIOLOGY+AND+MEDICINE&submit_search=Go%21).
En particular, en este notebook se tratan los siguientes temas:

- Preprocesamiento de datos
- Creación de vectores empleando Word2Vec de Gensim empleando la estructura modelo skipgram
- Entrenamiento de un modelo generador
- Ensayo del modelo empleando el método `most_similar` de Gensim para encontrar las palabras que más se relacionan con ciertas palabras de entrada
- Visualización de agrupación de vectores empleando TSNE y Plotly express
- Operaciones con embeddings, realizando tres tests de analogía

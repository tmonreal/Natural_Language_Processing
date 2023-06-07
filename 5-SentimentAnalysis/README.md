# Natural Language Processing

## Sentiment analysis con Embeddings + LSTM

<img width="959" alt="sentiment_analysis" src="https://github.com/tmonreal/Natural_Language_Processing/assets/84754265/17fac1bd-d133-4825-b51e-7504b80b08d3">


En este notebook se utilizan las críticas de compradores de ropa del dataset de Kaggle [Women's E-Commerce Clothing Reviews](https://www.kaggle.com/datasets/nicapotato/womens-ecommerce-clothing-reviews)
para que el sistema determine la evaluación del comprador y su crítica (cuantas estrellas le asigna al producto).

<p align="center">
  <img width="500" alt="sent" src="https://github.com/tmonreal/Natural_Language_Processing/assets/84754265/f74ce505-7715-4a55-9d03-ba506fe08dc8">
</p>
En particular, en este notebook se tratan los siguientes temas:

- Preprocesamiento de datos. Se transforma el problema de 5 clases a uno de 3 clases. El objetivo es definir si el cliente piensa que el producto es malo, bueno o muy bueno.
- División de los datos en set de entrenamiento y testeo. Se realiza oversampling al set de entrenamiento para tratar el desbalance de clases. 
- Entrenamiento de un modelo con Keras con capas de Embedding, capas LSTM bidireccionales, capas de dropout y capas densas.
- Entrenamiento de un modelo con Keras con capas de Embedding FastText, capas LSTM, capas de dropout y capas densas.
- Predicción del rating para diferentes reseñas de testeo empleando ambos modelos.


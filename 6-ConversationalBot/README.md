# Natural Language Processing

## LSTM Bot Q&A

<p align="center">
  <img width="691" alt="qaBot" src="https://github.com/tmonreal/Natural_Language_Processing/assets/84754265/e6b013bd-d003-4721-a771-4f8624a4257b">
</p>

En este notebook se crea de un bot capaz de responder a preguntas del usuario (Q&A) empleando [datos disponibles del challenge ConvAI2 (Conversational Intelligence Challenge 2) de conversaciones en inglés](http://convai.io/data/). 
En particular, en este notebook se tratan los siguientes temas:

- Preprocesamiento de datos para obtener word2idx, max_input_len, max_out_len y num_words_output empleando el Tokenizer de Keras. Padding  necesario para obtener encoder_input_sequences, decoder_output_sequences, decoder_targets. One Hot Encoding de los valores de salida del decoder (decoder_sequences).
- Empleo de embeddings de FastText para transformar los tokens de entrada en vectores. 
- Entrenamiento de un modelo basado en el esquema Seq2Seq con encoder-decoder usando Keras.
- Inferencias del modelo. Evaluación de conversaciones entre usuario y bot.

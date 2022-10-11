# PNL-TPs
Este repositorio contiene los trabajos prácticos de la materia Procesamiento del Lenguaje Natural de la Carrera de Especialización en Inteligencia Artificial (CEIA) de la FIUBA.

## TP1: vectorización de documentos

Se vectorizan y comparan documentos con diferentes representaciones.

![img1](images/01.jpg)

* Conceptos generales: corpus, documento, vocabulario.
* Representaciones: OHE, vectores de frecuencia y TF-IDF.
* Comparación de documentos: similitud coseno.

Colab: [Word2Vec](https://github.com/AnahiBazet/PNL-TPs/blob/main/TP1/DESAFIO1-Word2Vect.ipynb)

## TP2: bot basado en reglas

Se crea un bot basado en reglas que responde consultas sobre inteligencia artificial.

* Tokenización y lematización con spaCy.
* Tratamiento de stop words.
* Modelo DNN (Dense Neuronal Networks).
* Bag Of Word (BOW) vs. TF-IDF.

Colab: [Rule-Based Bot](https://github.com/AnahiBazet/PNL-TPs/blob/main/TP2/DESAFIO2-Rule_BasedBOT.ipynb)

## TP3: embeddings customizados

Se elige el libro "Harry Potter y La piedra filosofal", primero de la saga de la autora J.K. Rowling, para crear embeddings customizados de palabras basadas en ese contexto.

* Librería Gensim.
* Skip-Gram vs. CBOW de ventana 2 y 4.
* Graficos con T-SNE.

Colab: [Custom embeddings with Gensim](https://github.com/AnahiBazet/PNL-TPs/blob/main/TP3/DESAFIO3-CustomEmbeddingGensim%20v2.ipynb)

## TP4: predicción de la próxima palabra

Se elige el libro "Harry Potter y La piedra filosofal", primero de la saga de la autora J.K. Rowling, para entrenar los modelos. De esta manera, la predicción de la próxima palabra va a estar relacionada con el contexto de la historia presentada.

* LSTM many to one.
* Embeddings custom.
* Se compara una arquitectura simple sin bidireccionalidad con otros tres modelos: uno de arquitectura más compleja (con mayor profundidad y cantidad de neuronas), otro con bidireccionalidad, y por último, uno que combina ambos.

Colab: [Next word prediction](https://github.com/AnahiBazet/PNL-TPs/blob/main/TP4/DESAFIO4-Predicci%C3%B3nProximaPalabra.ipynb)

## TP5: análisis de sentimientos

Se utilizan las críticas de compradores de ropa para determinar la evaluación (cuántas estrellas les asignan al producto).

* Clasificación multi-clase.
* LSTM many to one.
* Embeddings Glove vs. FastText vs. custom.

Colab: [Sentiment analysis](https://github.com/AnahiBazet/PNL-TPs/blob/main/TP5/DESAFIO5-Sentiment_analysis_embedding_LSTM.ipynb)

## TP6: bot conversacional

Se construye un BOT en inglés para responder a preguntas del usuario (QA).

* LSTM encoder-decoder.
* Embeddings FastText.
* Con regularización vs. sin regularización.

Colab: [Bot QA](https://github.com/AnahiBazet/PNL-TPs/blob/main/TP6/DESAFIO6-Bot_QA.ipynb)

## ¡Gracias!
Por cualquier consulta me pueden contactar enviando un correo a anahibazet@gmail.com.



# Chatbot with Language Embeddings

This project involves creating and comparing language embeddings for building a chatbot, focusing on Tamil text data from *Ponniyin Selvan*. The assignment includes multiple steps to train, evaluate, and compare language embeddings generated from different models. The project was completed by **Nitin Sai Varma Indukuri** and **Lokesh Balamurugan**.

---

## Project Goals

1. **Train Language Embeddings**  
   - Use the provided Word2Vec notebook to train embeddings in Tamil.
   - Compare the Tamil embeddings with English embeddings to observe any differences in language characteristics.

2. **Develop RNN-based Embeddings**  
   - Build an RNN to train embeddings specifically for Tamil, rather than using the Keras Word2Vec model.
   - Demonstrate that the RNN-trained embeddings outperform the default Keras embeddings.

3. **Build and Compare Chatbots**  
   - Create a chatbot using the Tamil embeddings generated.
   - Compare the performance of this chatbot to another chatbot that uses English embeddings.
   - Optionally, integrate pre-trained embeddings in Tamil and evaluate their effect on chatbot performance against the custom embeddings.

4. **Evaluate Embedding Quality**  
   - Analyze the quality of embeddings from Word2Vec, the RNN model, and any pre-trained embeddings.
   - Use creative metrics and techniques, such as chatbot response accuracy, to demonstrate the superiority of one set of embeddings over another.

5. **Train and Compare Classic DNN Model**  
   - Train a shallow DNN model for embeddings and compare the results with those from the RNN-based embeddings.
   - Explore unique ways to assess embedding quality beyond chatbot performance, possibly involving other linguistic or semantic metrics.

---

## Project Structure

- **data/**
  - Contains the Tamil text data from *Ponniyin Selvan* and any necessary preprocessing scripts.

- **embedding/**
  - Code and resources for generating and saving embeddings, including Word2Vec and RNN-based models.

- **model/**
  - Stores trained model files, including Word2Vec, RNN embeddings, and shallow DNN models, saved for evaluation.

- **pickle/**
  - Serialized objects used in the project for easier access and reuse.

- **Notebooks:**
  - `1. ps_embedding_cbow.ipynb`: Training Word2Vec embeddings using CBOW on Tamil text.
  - `2. ps_rnn_cbow.ipynb`: Developing and training an RNN-based embedding model using CBOW.
  - `3. ps_rnn_direct.ipynb`: Direct training of RNN embeddings without CBOW.
  - `4. ps_dnn.ipynb`: Training a shallow DNN for embeddings.
  - `5. model_testing.ipynb`: Testing and evaluating the performance of different models.
  - `6. embeddings_evaluation.ipynb`: Comprehensive evaluation of embeddings from each model, including visualization and performance metrics.

---

## Setup Instructions

1. **Data Preparation**
   - Place *Ponniyin Selvan* text data in the `data/` directory.
   - Preprocess data to ensure compatibility with the embeddings model.

2. **Embedding Training**
   - Train Word2Vec embeddings using `1. ps_embedding_cbow.ipynb`.
   - Train RNN embeddings by running `2. ps_rnn_cbow.ipynb` and `3. ps_rnn_direct.ipynb`.

3. **Chatbot Creation and Testing**
   - Implement and test the chatbot using different embeddings.
   - Use `5. model_testing.ipynb` for testing and comparison.

4. **Evaluation**
   - Use `6. embeddings_evaluation.ipynb` to evaluate and compare embeddings quality.
   - Assess chatbot response accuracy, relevance, and language comprehension across embedding types.

---

## Evaluation Metrics

1. **Chatbot Performance**  
   - Compare chatbot accuracy, response quality, and language comprehension across embedding types.

2. **Semantic Similarity Tests**  
   - Measure how well each embedding type captures semantic relationships in Tamil.

3. **Embedding Visualization**  
   - Visualize embeddings to observe clustering of semantically similar words.

4. **Quantitative Scores**  
   - Evaluate using metrics such as cosine similarity and average response time.

---

---

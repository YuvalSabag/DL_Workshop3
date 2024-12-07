## **Deep Learning Workshop 3: Search Relevance with Siamese Neural Networks**

This project focuses on enhancing product search relevance for **[Home Depot](https://www.kaggle.com/c/home-depot-product-search-relevance/data)** using **Siamese Neural Networks**. The primary objective is to align user search queries with relevant product descriptions, ensuring an accurate and efficient search experience while driving sales. By incorporating both **character-level** and **word-level embeddings**, the model captures semantic relationships between search terms and product descriptions, enabling precise relevance score predictions.

The project is divided into two key stages:
1. **Character-Level Model**: Processes text at the character level to analyze fine-grained textual nuances and predict relevance.
2. **Word-Level Model**: Utilizes tokenized word embeddings to capture semantic context and improve performance.

&nbsp;  
### **Key Objectives**

- Develop a **Siamese Neural Network** to predict relevance scores between search queries and product descriptions.

- Implement two modeling approaches:
  1. **Character-Level Analysis**:
     - Preprocess text data into sequences of individual characters.
     - Train a Siamese Neural Network to evaluate search relevance based on character-level inputs.
     - Establish a **benchmark model** using count vectorization and statistical methods for comparison.
  2. **Word-Level Analysis**:
     - Tokenize search terms and product descriptions into words and specific character combinations.
     - Train embeddings using **Word2Vec** to capture semantic attributes of tokens.
     - Implement a Siamese Neural Network with **bidirectional LSTMs** to enhance contextual understanding.

- **Model Evaluation**:
  - Compare character-level and word-level models based on training, validation, and test datasets.
  - Analyze performance trends across metrics, highlighting areas for improvement in generalization.

- **Benchmarking**:
  - Establish baseline performance using classical regression methods, such as **Linear Regression** and **Random Forest**, with count vectorized text features.

- **Performance Metrics**:
  - Track and compare **MAE**, **MSE**, and **RMSE** for all models.
  - Visualize learning curves for insights into model convergence and potential overfitting.



# How vector embeddings and vector databases work

Enterprise vector data can be fed into an embedding model such as IBM’s watsonx.ai models or Hugging Face (link resides outside ibm.com), which are specialized to convert your data into an embedding by transforming complex, high-dimensional vector data into numerical forms that computers can understand. These embeddings represent the attributes of your data used in AI tasks such as classification and anomaly detection.

## Vector storage
Vector databases store the output of an embedding model algorithm, the vector embeddings. They also store each vector’s metadata, which can be queried using metadata filters. By ingesting and storing these embeddings, the database can then facilitate fast retrieval of a similarity search, matching the user’s prompt with a similar vector embedding. 

## Vector indexing
Storing data as embeddings isn't enough. The vectors need to be indexed to accelerate the search process. Vector databases create indexes on vector embeddings for search functionality. The vector database indexes vectors using a machine learning algorithm. Indexing maps vectors to new data structures that enable faster similarity or distance searches, such as nearest neighbor search between vectors.

## Similarity search based on querying or prompting
Querying vectors can be done via calculations measuring the distance between vectors using algorithms, such as nearest neighbor search. This measuring can be based on various similarity metrics such as cosine similarity, used by that index to measure how close or distant those vectors are. When a user queries or prompts an AI model, an embedding is computed using the same embedding model algorithm. The database calculates distances and performs similarity calculations between query vectors and vectors stored in the index. They return the most similar vectors or nearest neighbors according to the similarity ranking. These calculations support various machine learning tasks such as recommendation systems, semantic search, image recognition and other natural language processing tasks. 

# Use cases of vector databases 
The applications of vector databases are vast and growing. Some key use cases include:

**Semantic search**: Perform searches based on the meaning or context of a query, enabling more precise and relevant results. As not only words but phrases can be represented as vectors, semantic vector search functionality understands user intent better than general keywords. 

**Similarity search and applications**: Find similar images, text, audio or video data with ease, for content retrieval including advanced image and speech recognition, natural language processing and more. 

**Recommendation engines**: E-commerce sites, for instance, can use vector databases and vectors to represent customer preferences and product attributes. This enables them to suggest items similar to past purchases based on vector similarity, enhancing user experience and increasing retention.

**Conversational AI**: Improving virtual agent interactions by enhancing the ability to parse through relevant knowledge bases efficiently and accurately to provide real-time contextual answers to user queries, along with the source documents and page numbers for reference. 


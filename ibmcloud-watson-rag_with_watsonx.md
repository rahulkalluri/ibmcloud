# Vector databases and retrieval augmented generation (RAG)

Enterprises are increasingly favoring retrieval augmented generation (RAG) approach in generative AI workflows for its faster time-to-market, efficient inference and reliable output, particularly in key use cases such as customer care and HR/Talent. RAG ensures that the model is linked to the most current, reliable facts and that users have access to the model’s sources, so that its claims can be checked for accuracy. RAG is core to our ability to anchor large language models in trusted data to reduce model hallucinations. This approach relies on leveraging high-dimensional vector data to enrich prompts with semantically relevant information for in-context learning by foundation models. It requires effective storage and retrieval during the inference stage, which handles the highest volume of data. Vector databases excel at efficiently indexing, storing and retrieving these high-dimensional vectors, providing the speed, precision and scale needed for applications like recommendation engines and chatbots.

# Advantages of vector databases 
While it’s clear that vector database functionality is rapidly growing in interest and adoption to enhance enterprise AI-based applications, the following benefits have also demonstrated business value for adopters: 

**Speed and performance**: Vector databases use various indexing techniques to enable faster searching. Vector indexing along with distance-calculating algorithms such as nearest neighbor search, are particularly helpful with searching for relevant results across millions if not billions of data points, with optimized performance. 

**Scalability**: Vector databases can store and manage massive amounts of unstructured data by scaling horizontally, maintaining performance as query demands and data volumes increase.

**Cost of ownership**: Vector databases are a valuable alternative to training foundation models from scratch or fine-tuning them. This reduces the cost and speed of inferencing of foundation models.

**Flexibility**: Whether you have images, videos or other multi-dimensional data, vector databases are built to handle complexity. Given the multiple use cases ranging from semantic search to conversational AI applications, the use of vector databases can be customized to meet your business and AI requirements. 

**Long term memory of LLMs**: Organizations can start with a general-purpose models like IBM watsonx.ai’s Granite series models, Meta's Llama-2 or Google's Flan models, and then provide their own data in a vector database to enhance the output of the models and AI applications critical to retrieval augmented generation. 

**Data management components**: Vector databases also typically provide built-in features to easily update and insert new unstructured data. 

## Integration with your data ecosystem
Vector databases should not be considered as standalone capabilities, but rather a part of your broader data and AI ecosystem. Many offer APIs, native extensions or can be integrated with your databases. Since they are built to leverage your own enterprise data to enhance your models, you must also have proper data governance and security in place to ensure the data with which you are grounding these LLMs can be trusted. 

This is where a trusted data foundation plays an important role in AI, and that starts with your data and how it’s stored, managed and governed before being used for AI. Central to this is a data lakehouse, one that is open, hybrid and governed, such IBM watsonx.data, part of the watsonx AI data platform that fits seamlessly into a data fabric architecture. For example, IBM watsonx.data, is built to access, catalog, govern and transform all of your structured, semi-structured and unstructured data and metadata. You can then leverage this governed data and watsonx.data’s integrated vector database capabilities (tech preview Q4, 2023) for machine learning and generative AI use cases. 

## Vector database capabilities

**watsonx.ai** -> A next generation enterprise studio for AI builders to build, train, validate, tune and deploy both traditional machine learning and new generative AI capabilities powered by foundation models. Build a Q&A resource from a broad internal or external knowledge base with the help of AI tasks in watsonx.ai, such as retrieval augmented generation.
**watsonx.data** -> A fit-for-purpose data store built on an open data lakehouse architecture to scale AI workloads, for all your data, anywhere. Store, query and search vector embeddings in watsonx.data with integrated vector capabilities.
**IBM Cloud® Databases for PostgreSQL-** -> Our PostgreSQL database-as-a-service offering lets teams spend more time building with high availability, backup orchestration, point-in-time-recovery (PITR) and read replica with ease. PostgreSQL offers pgvector, an open-source vector extension that will be able to be configured with IBM Cloud PostgreSQLextensions (coming soon), providing vector similarity search capabilities.
**IBM Cloud Databases for Elasticsearch** -> Our Elasticsearch database-as-a-service comes with a full-text search engine, which makes it the perfect home for your unstructured text data. Elasticsearch also support various forms of  semantic (link resides outside ibm.com) similarity search. It supports dense vectors (link resides outside ibm.com) for exact nearest neighbor search, but it also provides built-in AI models to compute sparse vectors and conduct advanced similarity search (link resides outside ibm.com).

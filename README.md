# OskiBot
A chatbot application desgined specifically for UC Berkely University. So it can provide all the recent and academic information quickly to the students, professors and any individual.
Techstack Used **Langchain, RAG, AWS Bedrock, AWS Cloud Catalyst, BeautifulSoup, Flask, Amazon EC2, Amazon S3**.

+ **Note: We Only use the public information which is available on the UC Berkeley Website.**
+ Created crawler to scrape the university website to get public information to create a knowledge base.
+ Created Vector Embeddings using **Titan Text Embeddings v2** with a vector size of 1024.
+ Feed these vector embedding to **Claude Sonnet 3** model along with the query to get the relevant response.

From the queries it can be observed that since chatgpt does not have recent knowledge about UC Berkely, it failed to answer the queries, whereas the Oski Bot was able to retrieve relevant information from the knowledge base provided.

## Future Scope:

The chatbot can be extended to various functionalities such as
+ Checking Office hours of professors,
+ booking appointments,
+ the knowledge base can be made to update regularly. 
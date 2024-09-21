Individual final exam of CPSC 4830:

1. Compare Langchain vs GPT API in generating SQL query for a specific database (here is fraud_data.db). First, I connected the db file to SQLite to, then loaded the csv fie to Langchain to generate SQL queries. On another hand, GPT API doesn't allow to upload file so I provided the schema and prompts

Result: the SQL queries by GPT was not as accurate snce it doesn't allow file uploading

2. Compare Gensim + GloVe (Global Vectors for Word Representation) vs GPT API in finding similar text to keywords from PDF files. The text etracted from PDF was tokenized and stripped and similar words to keywords were identified and stored in BoW by GloVe model.

Result: performance of 2 mehods was similar but GPT API is more dynamic and easier to use in terms of modern language models  

Note: glove.6B.50d vectors file was downloaded from here https://nlp.stanford.edu/projects/glove/

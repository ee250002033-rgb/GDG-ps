in the task 2 of gdg ps1 we had to make a stock query answering chatbot using RAG model.
In my model I have used Mistral 7B which is a large ai language model similar to chatgpt and is open source . The 7B stands for 7 billion which refers to the number of parameters or learned weight it has.

i used a polygon news api key which provided the model with news sources to answer the query from.

the news api is free but is outdated and only contains data from sources of a certain time range, so it cant answer latest queries or sometimes give irrelevant answers.

the use of sentence transformers in the code is to convert text into vector embeddings which the model will do an similarity search for.

after the search it provides the user with the most relevant answer it can find.
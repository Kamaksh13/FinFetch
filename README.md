# FinFetch

FinFetch is a user-friendly application designed for effortless information retrieval from the stock market and financial domain. This tool enables users to input article URLs or upload text files containing URLs, ask questions, and receive relevant insights along with source URLs. Leveraging advanced technologies like LangChain, OpenAI embeddings, and FAISS, the tool provides swift and effective access to critical financial information.

Features

Load URLs or Upload Text Files:
Users can easily input single or multiple URLs.
Alternatively, upload text files containing URLs to fetch article content in bulk.
Article Content Processing:
The tool processes the fetched article content using LangChain's UnstructuredURL Loader, ensuring the data is clean and structured for analysis.
Embedding and Similarity Search:
Constructs an embedding vector using OpenAI's embeddings.
Leverages FAISS (Facebook AI Similarity Search), a powerful library, to enable fast and effective retrieval of relevant information based on user queries.
Interactive Query System:
Users can interact with a Large Language Model (LLM), such as ChatGPT, by inputting queries.
The tool provides answers along with source URLs, ensuring transparency and traceability of information.

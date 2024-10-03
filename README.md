# FinFetch

Fin Fetch is a user-friendly, AI-powered tool designed to streamline information retrieval from the stock market and financial news. By simply inputting article URLs or uploading text files containing URLs, users can ask specific questions and receive precise insights along with source URLs making financial research fast and effortless.

Key Features:

	•	URL Loading & Text File Support: Easily load article URLs or upload text files containing multiple URLs for content extraction.
	•	Content Processing with LangChain: Utilize LangChain’s UnstructuredURL Loader to process and structure article content for better analysis.
	•	Powerful Information Retrieval: Leverage OpenAI’s embeddings to construct a robust vector embedding, and use FAISS for rapid, similarity-based content retrieval.
	•	Interactive Querying: Ask questions and receive detailed answers from the integrated LLM (ChatGPT), complete with source URLs for transparency and further exploration.

Fin Fetch empowers financial analysts, researchers, and professionals to make informed decisions by extracting valuable insights from vast amounts of financial data with ease.


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

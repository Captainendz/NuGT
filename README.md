# RAG IMPLEMENTATION OF NuGT

An overview of the RAG architecture for improving and adapting LLM to the 3GPP standard documentation

## To run Locally

### All Requirements

- OpenAI - API key

### Steps

- Install dependencies by running `npm install`
- create a copy of the .env.example file by running `cp .env.example .env.local` in terminal
- update the env variables with the required keys in the `.env.local` file created in the previous step.
- Run the simple version by running `npm run chatbot`
- Run the RAG version by running `npm run chatbot:rag`

References
[Langchain documentation](https://js.langchain.com/docs/get_started/quickstart)
[OpenAI API](https://platform.openai.com/api-keys)
[Embeddings](https://platform.openai.com/docs/guides/embeddings)
[RAG Article](https://medium.com/@bijit211987/rag-vs-vectordb-2c8cb3e0ee52)
[VectorDB Service](https://qdrant.tech/)

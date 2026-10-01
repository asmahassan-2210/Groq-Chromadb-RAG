# Retrieval-Augmented Generation (RAG)

Retrieval-Augmented Generation combines information retrieval with a generative language model.

## How RAG Works

1. Documents are loaded from files.
2. The documents are divided into smaller chunks.
3. Each chunk is converted into a numerical embedding.
4. Embeddings are stored in a vector database.
5. A user's question is converted into an embedding.
6. Similar document chunks are retrieved.
7. The language model generates an answer using the retrieved context.

## Benefits

RAG can help a chatbot answer questions using a specific collection of documents rather than relying only on information learned during model training.

## Example

A university could store course notes, assignments, and policy documents in a vector database. Students could then ask questions and receive answers grounded in those documents.

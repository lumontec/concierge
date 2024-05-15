# concierge
Declarative first, simple agentic service for interacting with your data

** This project is still purely experimental at this stage, implementing a pure poc of the funcitionality

## Dependencies 

Install required llamaindex python deps:

```bash
$ pip install llama-index-core llama-index-readers-file llama-index-llms-ollama llama-index-embeddings-huggingface llama-index-embeddings-ollama
```

Install ollama cli for handling llms

```bash
$ curl -fsSL https://ollama.com/install.sh | sh
```
PS: not compat with wsl1 (only 2)

Install ollama repos, llm, embeddings:

```bash
$ ollama pull llama3
$ ollama pull nomic-embed-text
```






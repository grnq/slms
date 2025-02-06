# slms
"simple local mail search"

This code shows how you can use LlamaIndex and a local LLM to index and search through your email. This is all local, and no data is shared outside your local machine.

## Install and run a local LLM
1. [Install Ollama](https://ollama.com/download).
2. `$ollama run llama 3.2`
3. [Install llamaIndex](https://docs.llamaindex.ai/en/stable/getting_started/installation/).
4. Install Chroma to persist your database 
    + `pip install chromadb`
    + `pip install llama-index-vector-stores-chroma`
5. Then use `slms.ipynb`


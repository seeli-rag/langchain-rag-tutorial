# Langchain RAG Tutorial

[
    ![Open in Remote - Containers](
        https://xebia.com/wp-content/uploads/2023/11/v1.svg    )
](
    https://vscode.dev/redirect?url=vscode://ms-vscode-remote.remote-containers/cloneInVolume?url=https://github.com/seeli-rag/langchain-rag-tutorial.git
)

## Steps to run the application

1. Copy the file env-schema.txt to a file named .env and enter your OPENAI_API_KEY

2. Create the Chroma DB.

```python
python create_database.py
```

3. Query the Chroma DB.

```python
python query_data.py "How does Alice meet the Mad Hatter?"
```


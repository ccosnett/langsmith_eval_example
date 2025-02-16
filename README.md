## Evaluate a complex graph agent in langsmith using Evals

https://docs.smith.langchain.com/evaluation/tutorials/agents


# setup:

1. create a `.env` file:



```
OPENAI_API_KEY=<>


# langsmith
LANGSMITH_TRACING=true
LANGSMITH_ENDPOINT="https://api.smith.langchain.com"
LANGSMITH_API_KEY=<>


```
you can do this quickly with this command:

```
cp .env.example ./.env
code .env
```


2. install uv:

```
curl -LsSf https://astral.sh/uv/install.sh | sh
uv sync
source ./.venv/bin/activate
# streamlit ./dashboard.py
```
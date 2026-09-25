# LangGraph — Misc experiments

Smaller experiments that go beyond the three levels.

| Path | What it shows |
|---|---|
| [`subgraphs/insidenode.py`](subgraphs/insidenode.py) | Calling a compiled subgraph from inside a parent node |
| [`subgraphs/parentchildsubgraph.py`](subgraphs/parentchildsubgraph.py) | Adding a subgraph directly as a node when parent and child share state keys |
| [`tools-agent/tool_calling_agent.py`](tools-agent/tool_calling_agent.py) | Tool-calling agent with Tavily web search and a Groq LLM |
| [`twitter-agent/tweetthread.py`](twitter-agent/tweetthread.py) | Graph that picks a random ebook page, drafts a post with Groq and publishes it to X, with retry on errors |
| [`vectorstore.py`](vectorstore.py) | Long-term memory node backed by an AstraDB vector store and HuggingFace embeddings |

Set the API keys each script reads (Groq, Tavily, AstraDB, X) in a `.env` file before running.

# Reflexion agent

```shell
cp .env-example .env
```

In main.py, invoke the graph with a prompt of your choice.

The agent uses OpenAI and Tavily to answer your question after it improves the initial answer by questioning if there is
any missing or superfluous information, if there is, it generates search queries to get extra information.

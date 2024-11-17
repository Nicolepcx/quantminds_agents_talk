# QuantMinds LATS & Multi Agent Investment Analysis


This is the code for the Talk "Beyond Chatbots: Financial Innovation with Agentic LLMs". This repo draws inspiration from the paper [AutoGen: Enabling Next-Gen LLM Applications via Multi-Agent Conversation](https://arxiv.org/abs/2308.08155) by Wu et al., and from the [examples from LangGraph](https://github.com/langchain-ai/langgraph/tree/main/examples/multi_agent). 

![LATS.jpg](resources%2FLATS.jpg)

You will find two notebooks which you can directly open in Google Colab:

- 1. `LATS.ipynb`: This is the notebook shown during the talk for creating LATS. 
- 2. `LangGraph_multi_agents_investment_analysis.ipynb`: This is the notebook to create a multi-agent with LangGraph. 

For this, you will use the following tools:

  - [Exa](https://exa.ai/search), after account login, get your [API key here](https://docs.exa.ai/reference/getting-started-with-python). To find the exact content you're looking for on the web using embeddings-based search.  
  - [SerpApi here](https://serpapi.com/), after account login, get your [API key](https://serpapi.com/dashboard) to do look for existing patents.
  - [Python REPL](https://python.langchain.com/docs/integrations/tools/python/), please note that Python REPL can execute arbitrary code on the host machine (e.g., delete files, make network requests). Use with caution.
  - Tools to access and write to a `.txt` file and create a plot of historical prices.
- How to define utilities to help create the graph.
- How to create a team supervisor and the team of agents.


The interaction of the multi-agents looks like this:

![graph.jpeg](resources%2Fgraph.jpeg)
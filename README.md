# Hardware Recommendation

There's more and more people building in hardware. For that you need lots of components, which [McMaster-Carr](https://McMaster.com) sells ~700,000 of. The aim of this project is to:

1. Scrape all (or all relevant) products from McMaster
2. Embed the scraped items into a vector database (including CAD files)
3. Write a recommendation engine to find the best items for a project build
4. Order the items of McMaster to build the project

## Stack

Building this project, scaling needs to be in mind. The main goal is to reduce cost. So for the "RAG setup" we can use [LlamaIndex](https://www.llamaindex.ai) locally with [Ollama](https://ollama.com/). You can see more [here](https://docs.llamaindex.ai/en/stable/getting_started/starter_example_local/).

# LangChain for LLM Application Development

LangChain: LLM application need glue code.
- open-source deve framework for LLM applications
- python and javascript packages
- focus on composition and modularity

Components:
- models (integration)
- prompts (templates)
- indexes (doc loader/text splitter/vector stores/retrievers)
- chains (prompt + LLM + output parsing)
- agents

why prompt template vs fstrings?

- prompt can be long and detailed
- reuse good prompts when we can
- langchain provides commonly-used prompts

why output parser?

- although the output could look like a json format, but it is in `str`
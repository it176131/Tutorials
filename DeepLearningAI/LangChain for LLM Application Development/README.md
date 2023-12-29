# Introduction

By prompting an LLM, it is now possible to develop AI applications much 
faster than ever before.
But an application can require prompting an LLM multiple times and 
parsing its output, leading to a lot of "glue code".
LangChain makes this development process much easier.

LangChain started as an open source development framework for building LLM 
applications.
It came about as a solution to help develop complex applications with a 
more abstract, generalized approach.
There are two different packages: one for Python and one for Javascript.
The focus is on composition and modularity, having multiple individual 
components that can be used in conjunction or by themselves.
This course will cover the following components
- Models
  - LLMs
  - Chat Models
  - Text Embedding Models

- Prompts
  - Prompt Templates
  - Output Parsers
    - Retry/fixing logic
  - Example Selectors

- Indexes
  - Document Loaders
  - Text Splitters
  - Vector Stores
  - Retrievers

- Chains
  - Prompt + LLM + Output parsing
  - Building blocks for longer chains
  - Application specific chains

- Agents
  - Agent Types
    - Algorithms for getting LLMs to use tools
  - Agent Toolkits
    - Agents armed with specific tools for a specific application


After this course you should be able to quickly put together some 
applications using LangChain.
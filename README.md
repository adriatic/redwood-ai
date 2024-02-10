# This text is under development

---

## Introduction

[AI.JSX](https://docs.ai-jsx.com/) is a framework for building AI applications using Javascript and [JSX](https://www.codecademy.com/resources/docs/react/jsx). It assists dealing with _prompt engineering_, _Document Question + Answering_, and the use of external APIs - all commponents used in building LLM applications. 

The Fixie Console, accessible at https://console.fixie.ai, is the web interface where you can create and manage agents, and handle data sources for your applications. It's part of the Fixie platform for building applications with large language models, enabling natural language communication, data access, API calls, and more. For more precise description of Fixie.ai check the blog [Introducing Fixie.ai: A new way to build Large Langue Models](https://www.fixie.ai/blog/introducing-fixie-ai-a-new-way-to-build-with-llms). LLM stands for Large Language Model - a type of artificial intelligence model designed to understand, generate, and work with human language at a large scale

## Using Fixie-ai platform in the context of building RedwoodJS applications

It is envisioned to implement this project in three consecutive stages, each growing the complexity and functionality than the previous one.

### Stage 1 
#### Visual Studio Code and Fixie agent side by side

<img width="1812" alt="image" src="https://github.com/adriatic/redwood-ai/assets/2712405/46898190-00a6-418a-8225-5d420696682d">

The Fixie help window is rendered by a simple application that contains the Fixie agent using Redwood Corpus shown inside the i-Frame. There is no interaction between VSCode and Fixie agent, and the benefit of this implementation that it allows side by side view of the application code under development and the Fixie help assisting the developer.

Note that this implementation offers the testing and tunning of the Redwood Corpus - probably the key functionality of the this whole project. As the developer works in the VSCode, it can converse with the Redwood Agent using the copy and paste to define the prompts and utilize the responses.

How valuable is this approach: in my view it is pretty useful - as it is more powerful than our current use of VSCode and RedwoodJS docs:

<img width="1878" alt="image" src="https://github.com/adriatic/redwood-ai/assets/2712405/a1573038-91b9-44d2-99df-2370d53c95ce">

**Note: a very easy improvement here is to merge the Git-Github Corpus with Redwood Corpus, allowing this upgraded agent to help with Redwood as well as with Github**

<img width="943" alt="image" src="https://github.com/adriatic/redwood-ai/assets/2712405/38f154a9-18ba-4e1f-855a-1d9cd8ddc5f2">


### Stage 2
#### Visual Studio Code with RW-Fixie extension



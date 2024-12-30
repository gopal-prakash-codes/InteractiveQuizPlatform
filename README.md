
</div>

[Haystack](https://haystack.deepset.ai/) is an end-to-end LLM framework that allows you to build applications powered by
LLMs, Transformer models, vector search and more. Whether you want to perform retrieval-augmented generation (RAG),
document search, question answering or answer generation, Haystack can orchestrate state-of-the-art embedding models
and LLMs into pipelines to build end-to-end NLP applications and solve your use case.

## Installation

The simplest way to get Haystack is via pip:

```sh
pip install haystack-ai
```

Install from the `main` branch to try the newest features:
```sh
```

Haystack supports multiple installation methods including Docker images. For a comprehensive guide please refer
to the [documentation](https://docs.haystack.deepset.ai/docs/installation).

## Documentation

## Features

> [!IMPORTANT]
- **Technology agnostic:** Allow users the flexibility to decide what vendor or technology they want and make it easy to switch out any component for another. Haystack allows you to use and compare models available from OpenAI, Cohere and Hugging Face, as well as your own local models or models hosted on Azure, Bedrock and SageMaker.
- **Explicit:** Make it transparent how different moving parts can “talk” to each other so it's easier to fit your tech stack and use case.
- **Flexible:** Haystack provides all tooling in one place: database access, file conversion, cleaning, splitting, training, eval, inference, and more. And whenever custom behavior is desirable, it's easy to create custom components.
- **Extensible:** Provide a uniform and easy way for the community and third parties to build their own components and foster an open ecosystem around Haystack.

Some examples of what you can do with Haystack:

-   Build **retrieval augmented generation (RAG)** by making use of one of the available vector databases and customizing your LLM interaction, the sky is the limit 🚀
-   Perform Question Answering **in natural language** to find granular answers in your documents.
-   Perform **semantic search** and retrieve documents according to meaning.
-   Build applications that can make complex decisions making to answer complex queries: such as systems that can resolve complex customer queries, do knowledge search on many disconnected resources and so on.
-   Scale to millions of docs using retrievers and production-scale components.
-   Use **off-the-shelf models** or **fine-tune** them to your data.
-   Use **user feedback** to evaluate, benchmark, and continuously improve your models.
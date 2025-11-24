---
title: Microsoft.Extensions.AI
description: Learn about the Microsoft.Extensions.AI library for building AI applications in .NET
author: IEvangelist
ms.author: dapine
ms.date: 11/24/2024
ms.topic: overview
---

# Microsoft.Extensions.AI

Microsoft.Extensions.AI is a set of core .NET libraries developed in collaboration with developers across the .NET ecosystem, including Semantic Kernel. These libraries provide a unified layer of C# abstractions for interacting with AI services, such as small and large language models (SLMs and LLMs), embeddings, and middleware.

## Overview

The Microsoft.Extensions.AI libraries provide consistent APIs for AI services, enabling developers to:

- Write code that works across multiple AI service providers
- Leverage dependency injection and configuration patterns familiar to .NET developers
- Build middleware pipelines for cross-cutting concerns
- Switch between different AI providers with minimal code changes

## Installation

Install the Microsoft.Extensions.AI packages from NuGet:
```bash
dotnet add package Microsoft.Extensions.AI
dotnet add package Microsoft.Extensions.AI.Abstractions
```

## Core Concepts

### IChatClient

The `IChatClient` interface provides a unified abstraction for chat-based AI interactions.

### IEmbeddingGenerator

The `IEmbeddingGenerator` interface provides abstractions for generating embeddings from text.

### Middleware Pipeline

Microsoft.Extensions.AI supports middleware patterns for implementing cross-cutting concerns like logging, telemetry, and rate limiting.

## Experimental Features

The following features are currently experimental and may change in future releases.

### Chat Reduction (experimental)

> [!WARNING]
> This feature is experimental and subject to change.

Chat reduction optimizes conversation history by intelligently summarizing or reducing token usage while maintaining context.

**Usage:**

[Add detailed content from Jeremy's materials]
```csharp
// Example code will go here
```

### Tool Reduction (experimental)

> [!WARNING]
> This feature is experimental and subject to change.

Tool reduction optimizes the tools/functions provided to AI models by selecting the most relevant subset based on the conversation context.

**Usage:**

[Add detailed content from Jeremy's materials]
```csharp
// Example code will go here
```

### Image Generation (experimental)

> [!WARNING]
> This feature is experimental and subject to change.

Image generation support enables AI models to create images based on text prompts using the Microsoft.Extensions.AI abstractions.

**Usage:**

[Add detailed content from Jeremy's materials]
```csharp
// Example code will go here
```

## Preview Features

The following features are available in preview.

### Data Ingestion (preview)

> [!NOTE]
> This feature is in preview and may be subject to changes.

Data ingestion provides building blocks for importing and processing data from various sources into AI applications.

**Key capabilities:**

[Add detailed content from "Data Ingestion Building Blocks Preview - Nov 24"]
```csharp
// Example code will go here
```

## See Also

- [.NET AI Documentation](../index.yml)
- [Semantic Kernel](https://learn.microsoft.com/semantic-kernel/)
- [Azure OpenAI Service](https://learn.microsoft.com/azure/ai-services/openai/)

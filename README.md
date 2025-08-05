# CAMEL-AI for Luta

CAMEL-AI (Communicative Agents for AI Society Study) - Customized for Luta platform.

## Overview

This is a customized version of the CAMEL-AI framework, adapted for the Luta platform's specific needs in Buddhist text processing and AI agent development.

## Key Features

- Multi-agent conversation framework
- Role-playing capabilities for different AI personas
- Extensive toolkits for various AI tasks
- Support for multiple LLM backends

## Installation

This package is designed to be used as part of the Luta API system and should be installed via the main project's dependency management.

## Usage

```python
from camel.agents import ChatAgent
from camel.models import ModelFactory

# Initialize a chat agent
model = ModelFactory.create(model_platform="openai", model_type="gpt-4")
agent = ChatAgent(model=model)

# Use the agent
response = agent.step("Hello, tell me about Buddhism")
```

## Development

This is a customized fork of the original CAMEL-AI project, adapted for the Luta platform's Buddhist text processing requirements.

Original repository: https://github.com/camel-ai/camel
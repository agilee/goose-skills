# AEO Setup

Set up [Goose AEO](https://github.com/athina-ai/goose-aeo) for a domain. Walks through configuration, API keys, competitor discovery, and query generation interactively.

## What It Does

1. Asks for your company domain and competitors
2. Checks which AI provider API keys are available
3. Initializes config and database
4. Auto-discovers competitors (via Perplexity)
5. Generates sample queries for review, then a full query set

## Prerequisites

- Node.js >= 20
- At least one AI provider API key (Perplexity, OpenAI, Gemini, Grok, Claude, or DeepSeek)
- OpenAI API key for query generation and analysis

## Usage

```
/aeo-setup
```

After setup, use `/aeo-run` to run your first visibility analysis.

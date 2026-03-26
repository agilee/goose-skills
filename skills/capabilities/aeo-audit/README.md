# AEO Audit

Audit a website for AI search readability using [Goose AEO](https://github.com/athina-ai/goose-aeo). Scrapes pages and scores each one across 6 dimensions.

## What It Does

1. Scrapes your website pages
2. Scores each page for AI search readability (0-10)
3. Evaluates 6 dimensions: positioning clarity, structured content, query alignment, technical signals, content depth, comparison content
4. Provides actionable recommendations for improvement

## Prerequisites

- Goose AEO must be initialized first (use `/aeo-setup`)
- OpenAI API key for scoring

## Usage

```
/aeo-audit
```

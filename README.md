# Coding Research Assistant

An intelligent research assistant that helps developers discover and analyze developer tools, libraries, and technologies using AI-powered web scraping and analysis.

## Overview

This tool automates the process of researching developer tools by:
- Extracting tool names from relevant articles and blog posts
- Scraping official websites and documentation
- Analyzing tools from a developer's perspective (pricing, tech stack, API availability)
- Providing concise recommendations based on your specific needs

## Features

- **Smart Tool Discovery**: Automatically finds relevant tools from articles and comparison posts
- **Comprehensive Analysis**: Extracts key information like pricing models, open-source status, supported languages, and integrations
- **Developer-Focused**: Prioritizes information relevant to programmers (APIs, SDKs, language support)
- **Structured Output**: Returns well-organized data using Pydantic models
- **AI-Powered Recommendations**: Provides concise, actionable advice based on analyzed data

## Tech Stack

- **Python 3.13**
- **LangGraph**: Workflow orchestration and state management
- **OpenAI GPT-4**: Natural language processing and analysis
- **Firecrawl**: Web scraping and content extraction
- **Pydantic**: Data validation and structured outputs
- **python-dotenv**: Environment variable management

## How It Works

1. **Tool Extraction**: Searches for articles about your query and extracts specific tool names
2. **Research Phase**: Finds official websites for each extracted tool
3. **Analysis**: Uses AI to analyze each tool's content for developer-relevant information
4. **Recommendations**: Provides concise recommendations based on the analysis


## Configuration

The tool uses structured prompts optimized for developer tool analysis. You can customize the analysis criteria by modifying the prompts in `src/prompts.py`.

## Requirements

- Python 3.8+
- Firecrawl API key
- OpenAI API key

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request




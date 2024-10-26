# claude-pipe
Claude Pipe for Text Generation Web UI
# Claude Pipe for Text Generation Web UI

## Description
A Python-based pipeline for integrating Anthropic's Claude AI models with Text Generation Web UI. This implementation supports:
- Multiple Claude models (Haiku, Opus, Sonnet)
- Streaming responses
- Image handling capabilities
- System message management
- Both sync and async responses

## Features
- Multi-modal support (text and images)
- Built-in safety limits for images
- Proper error handling and logging
- Streaming and non-streaming response support
- Pydantic models for validation

## Requirements
- requests
- pydantic
- Anthropic API key

## Setup
1. Clone the repository
2. Install requirements: `pip install -r requirements.txt`
3. Set your Anthropic API key as an environment variable
4. Configure with your Text Generation Web UI

## Usage
Can be used as a custom endpoint in Text Generation Web UI for accessing Claude models.

## Note
This is an integration tool and requires valid API credentials from Anthropic.

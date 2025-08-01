# 🧠 Project Overview
This project is a practical implementation of the Model Context Protocol (MCP), inspired by the "MCP: Build Rich-Context AI Apps" course by DeepLearning.AI.

While the course focused on Anthropic's Claude, I completed all exercises using OpenAI's API instead — building an MCP-compatible assistant that can use tools, fetch real-world data, and access files through connected servers.

## 🔨 What I built
MCP Client: A tool-using chatbot powered by OpenAI (supports prompt injection and tool calling logic)

Custom MCP Server: research_server.py — takes a topic and number of articles, fetches relevant content

### Connected Servers:

- filesystem: read files from local disk

- fetch: pull web page content from URLs

- Prompt Logic: Allows the assistant to ask relevant questions, then call the appropriate tool

## Acknowledgements
https://learn.deeplearning.ai/courses/mcp-build-rich-context-ai-apps-with-anthropic/lesson/fkbhh/introduction

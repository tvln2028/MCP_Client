# MCP Client

A premium client implementation for Model Context Protocol (MCP), featuring both a interactive CLI client and a robust FastAPI server. This client enables seamless integration with HRMS and other MCP-compatible servers, orchestrating intelligent tool execution through advanced LLMs.

## Features

- **FastAPI Server**: High-performance asynchronous endpoints for chat and assistant interactions.
- **Interactive CLI Client**: Clean, responsive terminal interface for real-time command-line conversations.
- **Multi-Server MCP Client**: Support for concurrent connection to multiple stdio-based MCP servers.
- **LangChain & LangGraph Orchestration**: Leverages state-of-the-art agent architectures with memory savers.

## Setup

1. Clone the repository and navigate to the directory:
   ```bash
   git clone https://github.com/tvln2028/MCP_Client.git
   cd MCP_Client
   ```

2. Install dependencies (recommended to use `uv`):
   ```bash
   uv sync
   ```

3. Configure your `.env` file based on `.env.sample`.

4. Run the FastAPI server:
   ```bash
   python fastapi_server.py
   ```

5. Or run the CLI client:
   ```bash
   python main.py
   ```

## Contributors

No contributors specified.

# OpenAPI to OpenAI Assistant Mapping

This repository provides a framework for mapping OpenAPI specifications to OpenAI's Assistant API, enabling seamless API integration and function calling. It includes reusable Python classes and a practical Jupyter notebook demonstrating how to query CoinGecko's cryptocurrency API as an example.

## Features

- **Mapping OpenAPI Specs:** Convert OpenAPI endpoints into callable functions for OpenAI's Assistant API.
- **Thread Management:** Create, retrieve, and manage message threads with OpenAI assistants.
- **Streaming Responses:** Stream OpenAI assistant responses in real time and handle further API interactions as required.
- **Practical Example:** Demonstrates querying CoinGecko's API using OpenAPI specifications.


## Prerequisites
- Python (>= 3.11.4)
- OpenAI API key

## Setup Instructions

```bash
python3 -m venv venv
source venv/bin/activate
```

### 2. Install the required Python packages:
```bash
pip install -r requirements.txt
```

### Usage

1. Set up your OpenAI API credentials:
    - Add your OpenAI API key to the environment or directly in the code.
  
2. Update the assistant ID and OpenAPI spec file path in the provided Jupyter notebook.

3. Run the notebook step-by-step to map OpenAPI functions to the OpenAI assistant and query the CoinGecko API.
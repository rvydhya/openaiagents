# OpenAI Agents Python Examples

This repository contains several Jupyter Notebooks demonstrating the use of the [OpenAI Agents Python](https://openai.github.io/openai-agents-python/) framework. The examples cover a variety of use cases including:

- Basic agent interactions (e.g., asking for a capital city)
- Asynchronous operation with streaming responses
- Function calls with decorators
- Handling multiple agent handoffs
- Guardrails and input validation

## Folder Structure

- **1 Demo.ipynb**  
  A basic example of using an agent to answer a query.
  
- **1.1 Demo async.ipynb**  
  Demonstrates asynchronous operation with agents.
  
- **1.2 Demo Stream.ipynb**  
  Shows how to stream responses from an agent.
  
- **2 function call.ipynb**  
  Contains an example of using function calls within an agent context.
  
- **2.1 function call with decorator.ipynb**  
  An example demonstrating the use of a decorator for function tools.
  
- **3 multiple agents.ipynb**  
  Illustrates using multiple agents for specialized tasks.
  
- **4 guard rails.ipynb**  
  Uses guardrails to validate and manage user input.
  
- **5 Chat.ipynb**  
  A conversational example with trace support.
  
- **6 Tools WebSearch.ipynb**  
  Demonstrates web search functionality integrated with the agent.
  
- **6.1 Tools FileSearch.ipynb**  
  Shows file search and vector store integration.
  
- **7 Handoffs.ipynb**  
  An example that uses language-specific handoffs between agents.

## Prerequisites

- Python 3.10+
- [Playwright](https://playwright.dev/)
- Required packages are listed in [requirements.txt](c:\work\openaiagents\requirements.txt)

## Setup

1. Copy the provided `.env` file and update the `OPENAI_API_KEY` with your valid API key.
2. Create and activate a virtual environment.
3. Install dependencies:

    ```sh
    pip install -r requirements.txt
    ```

4. Optionally, install and configure Playwright for browser automation if needed.

## Running the Examples

Each notebook demonstrates a different aspect of the OpenAI Agents framework. Open the notebooks in Visual Studio Code or Jupyter Notebook and run the cells sequentially. For synchronous examples, you can also run the Python scripts directly using:

```sh
python <notebook_exported_script.py>
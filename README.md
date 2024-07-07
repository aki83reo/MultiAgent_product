# MultiAgent_product
# Multi-Agent Service Query System

A dynamic multi-agent service query system leveraging FAISS for similarity search and LangChain for intelligent query routing. This project supports various service queries, including AC repair, fan repair, electrician services, microwave repair, and plumbing, dynamically directing queries to the appropriate agent for accurate results.

## Features

- **Dynamic Query Routing**: Uses LangChain to route queries to the correct service category based on natural language input.
- **Efficient Similarity Search**: Utilizes FAISS for fast and accurate similarity search.
- **Multi-Agent System**: Supports multiple agents for different service categories.
- **Scalable and Extendable**: Easily add new service categories and agents.

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/aki83reo/MultiAgent_product.git
    cd MultiAgent_product
    ```

2. Create and activate a virtual environment:
    ```sh
    python -m venv env
    source env/bin/activate  # On Windows, use `env\Scripts\activate`
    ```

3. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. Prepare your dataset and ensure it includes relevant columns for service, subservice_name, and subservice_charge.
2. Modify the `file_path` variable in the script to point to your dataset.
3. Run the script to start the multi-agent service query system:
    ```sh
    python main.py
    ```

## Example Queries

- "I need the best AC service under 2000"
- "I need to fix my fan motor"
- "I need an electrician for wiring"
- "My microwave is not heating"
- "I need a plumber to fix my sink"

## Troubleshooting

If you encounter the following error:
```sh
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/aki83reo/MultiAgent_product.git'

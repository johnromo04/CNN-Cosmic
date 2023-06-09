# GPT LLM PDF TEST

We will be testing how LLMs from Openai perform on scientific docs.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [OpenAI API Keys](#openai-api-keys)
- [Running the Application](#running-the-application)


## Installation

To run this project, you'll need to have the following packages installed:

- langchain
- openai
- streamlit
- tiktoken
- chromadb
- pypdf
- pycryptodome

You can install these packages using `pip`:

Virtual Enviornment may be needed. Anaconda, Miniconda, etc.

```shell
pip install langchain openai streamlit tiktoken chromadb pypdf pycryptodome

## Usage

Examples and instructions on how to use the project.

## Example

This code demonstrates a PDF text analysis and interaction application. It utilizes various libraries and techniques to extract information from a PDF file and provide interactive prompts similar to Chat-based Language Models (LLMs).

The code performs the following steps:

1. Reads a PDF file and extracts its contents.
2. Applies natural language processing techniques to understand the text and extract relevant information.
3. Sets up an interactive prompt system where users can engage with the extracted information and ask questions or provide prompts.
4. Utilizes underlying language models, such as Chat GPT, to generate responses and provide insightful outputs based on user interactions.

By combining PDF processing, natural language understanding, and language generation capabilities, this code enables the exploration and interaction with PDF content in a conversational manner.

You can run the code by following the installation instructions and launching the application. Once the PDF content is processed, you can engage with the application by interacting with the prompts and receiving responses in a chat-like manner.

## OpenAI API Keys

To utilize the OpenAI API features in this project, you need to import and configure your OpenAI API keys. Follow the steps below to add your API keys:

1. Create a new file named `api_keys.py` in the root directory of the project.
2. In the `api_keys.py` file, use the following format:

    ```python
    # api_keys.py

    OPENAI_API_KEY = 'your-openai-api-key-goes-here'
    ```

3. Replace `'your-openai-api-key-goes-here'` with your actual OpenAI API key. Ensure you keep the single quotes around the API key string.

Make sure to keep your API keys secure and avoid sharing them publicly.

## Running the Application

You can run the application via the command line using the following command:

```shell
streamlit run LLM.py

Ensure you are in the project's root directory before executing the command. This will launch the application and make it accessible through your web browser.









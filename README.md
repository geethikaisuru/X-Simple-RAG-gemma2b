# README for notebook.ipynb
This Jupyter notebook is used to interact with the OpenAI API and the Ollama model, load and split a PDF document, generate prompts, and retrieve answers to questions based on the document's content.

# Dependencies
        os
        dotenv
        langchain_openai.chat_models
        langchain_openai.embeddings
        langchain_community.llms
        langchain_community.embeddings
        langchain_core.output_parsers
        langchain_community.document_loaders
        langchain.prompts
        langchain_community.vectorstores
        operator
        Output

The script generates answers to a set of predefined questions based on the content of a PDF document. The answers are printed to the console.

# Note
Ensure that the required packages and modules are installed and accessible in your Python environment. Also, make sure to have a .env file in your project directory with the OpenAI API key defined. The PDF document to be loaded should be in the same directory as the notebook and its name should be "novel.pdf".
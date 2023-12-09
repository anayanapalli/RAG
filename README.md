# Retrieval Augmented Generation

## Overview
This repository contains a iPython notebook that leverages the LangChain library, OpenAI's GPT-3.5 Turbo, and FAISS (Facebook AI Similarity Search) to perform document retrieval and question answering. The script processes a PDF document and answers a set of predefined questions using a combination of language models and embeddings.
## Prerequisites
Before running the script, ensure you have the following prerequisites installed:

- Python 3.x
- LangChain library: `pip install langchain`
- OpenAI Python library: `pip install openai`
- dotenv library: `pip install python-dotenv`
- Faiss library: `pip install faiss`

## Usage

1. Clone this repository:

```
git clone https://github.com/yourusername/your-repository.git
```

2. Navigate to the project directory:

```bash
cd your-repository
```

3. Create a virtual environment (optional but recommended):

```python
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
```
4. Install dependencies:

```bash
pip install -r requirements.txt
```

5. Set up your OpenAI API key:
Create a .env file in the project root and add your OpenAI API key:

```bash
OPENAI_API_KEY=your-api-key
```

6. Run the notebook 😊


## Script Overview
- Step 1: Import necessary libraries and set up OpenAI API key from environment variable.
- Step 2-9: Use LangChain library to process a PDF document and generate embeddings.
- Step 10-13: Define a list of questions related to the document.
- Step 14-20: Iterate through the list of questions, generate responses using GPT-3.5 Turbo and RetrievalQA model, and print the results.

## Customization
Feel free to customize the script by modifying the list of questions, adjusting the maximum tokens for GPT-3.5 Turbo, or exploring other configurations provided by LangChain.

## Disclaimer
This script relies on OpenAI's GPT-3.5 Turbo, and you are responsible for complying with OpenAI's usage policies and terms.

Please refer to the respective documentation for LangChain and OpenAI for more details.

Happy coding!






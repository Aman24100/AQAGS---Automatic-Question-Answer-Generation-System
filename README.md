# Automatic Question-Answer Generation System

An end-to-end pipeline that takes any text or PDF (in any language) as input and generates structured question–answer pairs in Hindi, English, or other languages. Built using LangChain and prompt engineering, this project supports multiple question formats: Multiple Choice Questions (MCQs), Short Answer, Long Answer, True/False, and Fill in the Blanks.

## Features

- **Multilingual Input & Output**  
  - Accepts plain text or PDF in any language.  
  - Generates Q&A in Hindi, English, or other supported languages.

- **Flexible Question Types**  
  - MCQs (with options and correct answer)  
  - Short Answer  
  - Long Answer  
  - True/False (with explanation)  
  - Fill in the Blanks

- **Custom Question Count**  
  - Specify total number of questions; automatic distribution across types or focus on a single type.

- **Modular & Extensible**  
  - Built on LangChain’s pipelines and prompt templates.  
  - Swap LLM models (e.g., GPT-3.5, GPT-4, Azure OpenAI).

- **Batch Processing**  
  - Process multiple files in one run.  
  - Output saved in JSON, CSV, or plain text.

## Prerequisites

- Python 3.9+  
- OpenAI API Key (or Azure OpenAI) set as environment variable:  
  ```bash
  export OPENAI_API_KEY="your_openai_api_key"

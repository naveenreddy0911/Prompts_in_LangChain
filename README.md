# Prompts in LangChain

This repository demonstrates how to create and use prompt templates with LangChain for various NLP tasks. It includes structured prompt construction, dynamic UI input handling, and chaining components like message history and chat models.
This project is especially helpful for building and testing **custom prompts** using both closed-source and **free open-source models** like those from Hugging Face.

## 📄 File Descriptions

- `prompt_template.py`  Creates and formats standard prompts using LangChain’s `PromptTemplate`.
- `chat_prompt_template.py`  Defines chat-oriented prompts using `ChatPromptTemplate`, useful for chat-based LLMs.
- `prompt_ui.py`  A UI utility that gathers input dynamically for prompt generation.
- `chatbot.py`  Orchestrates prompt creation, model calls, and conversation flow.
- `message_placeholder.py`  Provides placeholders for user and assistant messages during prompt construction.
- `messages.py`  Manages message roles and templates for use in chat chains.
- `template.json`  A sample JSON-based prompt template.

## Environment Variables

To use this project, you need to set API keys in a .env file in the root directory.
### 📄 .env file format
```env
OPENAI_API_KEY="your_openai_key"
HUGGINGFACEHUB_API_KEY="your_huggingfacehub_key"
```

### Dont have closed-source API key ? 
Refer to the repo [**Models_in_LangChain**](https://github.com/yourusername/Models_in_LangChain) for using open-sourced Hugging Face chat models (via API or locally).

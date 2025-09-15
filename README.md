# Conversation Management & Classification using Groq API

## Overview
This project demonstrates how to manage conversation history and extract structured information from chats using the **Groq API** with OpenAI SDK compatibility. The notebook implements:

1. **Conversation Management** – storing, truncating, and summarizing chat history.
2. **JSON Schema Classification** – extracting structured data (name, email, phone, location, age) from user messages.

It’s a framework-free Python implementation, suitable for showcasing **AI-powered conversational data handling**.

---

## Features

- **Conversation History Management**
  - Stores user and assistant messages.
  - Periodically summarizes conversations to keep them concise.
  - Configurable truncation by message count or character length.

- **Information Extraction**
  - Extracts structured details from chat using JSON schema.
  - Supports API-based extraction with a local fallback.
  - Validates parsed data against the schema.

- **Interviewer-Friendly Notebook**
  - Well-documented code with Markdown explanations.
  - Demonstrates usage with sample chats and outputs.
  - Framework-free and ready to run in Google Colab.

---

## Getting Started

### Prerequisites
- Python 3.8+
- Google Colab (recommended)
- Git (for versioning)
- Groq API key / OpenAI-compatible API key

### Installation
Install required Python packages:

```bash
pip install openai jsonschema


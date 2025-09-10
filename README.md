# AI Chatbot Using OpenAI API

## Overview
This project is a simple Python-based conversational AI chatbot that integrates with the OpenAI API to process user queries and generate intelligent responses. It demonstrates foundational software engineering principles like modular design, error handling, and API integration. Built as part of a portfolio to showcase skills in Python, NLP, and software development.

## Features
- Handles user input via command-line interface.
- Uses OpenAI's GPT model for natural language understanding and response generation.
- Includes basic error handling for API quota issues and invalid inputs.
- Modular structure for easy maintenance and scalability.

## Technologies Used
- Python 3.x
- OpenAI Python library
- Environment variables for API key management

## Installation
1. Clone the repository: `git clone https://github.com/Samyuktha0/AI-Chatbot-Using-OpenAI-API.git`
2. Install dependencies: `pip install openai python-dotenv`
3. Set up your OpenAI API key in a `.env` file: `OPENAI_API_KEY=your_api_key_here`
4. Run the script: `python chatbot.py`

## Usage
- Run the script and enter your queries in the prompt.
- Type 'exit' to end the conversation.

## Example
User: What's the capital of France?  
Chatbot: The capital of France is Paris.

## Limitations
- Requires an active OpenAI API key with sufficient quota.
- Basic implementation; not production-ready without additional security features.

## License
MIT License

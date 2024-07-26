# OpenAI Chatbot

This project is a simple chatbot that uses the OpenAI API to generate responses based on user input. The bot communicates using the GPT-3.5-turbo model (or GPT-4 if you have access).

## Prerequisites

- Python 3.7 or higher
- `openai` Python package

## API Key Configuration
Replace 'your-api-key' in the script with your actual OpenAI API key.
```
client = OpenAI(api_key='you api key )
```


## example of the output

```
You: Hello! (userinput)
AI assistant: Hi there! How can I assist you today?

You: Tell me a joke.
AI assistant: Why don't scientists trust atoms? Because they make up everything!

You: q
Goodbye!
```

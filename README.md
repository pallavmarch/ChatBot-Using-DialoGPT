# ChatBot Using DialoGPT

## Description
This repository contains the code for a simple and interactive ChatBot built using Microsoft's DialoGPT model. The ChatBot engages in conversations, responds to user inputs, and provides fallback responses when it does not understand the input. The project demonstrates the use of the Hugging Face Transformers library to implement a conversational AI model.

## Features
- Initiates a conversation with a greeting.
- Responds to user inputs.
- Handles conversation history to provide contextually relevant responses.
- Provides fallback responses for unknown inputs.

## Requirements
- Python 3.6 or higher
- `numpy` library
- `torch` library
- `transformers` library from Hugging Face

## Code Overview
- **ChatBot Class**: Initializes the ChatBot, handles user input, generates responses, and provides fallback responses.
- **Main Loop**: Continuously prompts the user for input and generates appropriate responses until the user decides to quit.

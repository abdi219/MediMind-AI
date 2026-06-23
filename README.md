# AI-Powered Health Query Chatbot

This project was completed as part of the AI/ML Engineering Internship at DevelopersHub Corporation.

## Project Overview

This project focuses on developing an AI-powered health information chatbot that answers general health-related questions using the Llama 3.3 70B Instruct model through the Hugging Face Router API.

The chatbot incorporates prompt engineering, safety filtering, and responsible AI practices to provide concise, educational, and user-friendly health information while encouraging consultation with healthcare professionals.

## Objective

The objective of this project is to build a safe and reliable conversational AI system capable of providing general health information while preventing harmful, misleading, or unsafe medical guidance.

## Technologies Used

- Python
- Hugging Face Router API
- Llama 3.3 70B Instruct
- Requests Library
- Python Dotenv

## Key Features

- Answers general health-related questions
- Uses a large language model for natural language responses
- Implements prompt engineering for controlled behavior
- Blocks harmful and high-risk queries through keyword filtering
- Provides concise and easy-to-understand responses
- Includes emergency safety guidance for critical situations
- Interactive command-line chatbot interface

## Safety Measures

The chatbot follows several safety guidelines:

- Does not diagnose medical conditions
- Does not prescribe medications or dosages
- Detects and blocks harmful or dangerous queries
- Encourages users to seek professional medical advice
- Provides emergency recommendations for severe symptoms

## System Components

### API Configuration

- Secure loading of Hugging Face API credentials using environment variables
- Integration with the Hugging Face Router endpoint

### Prompt Engineering

- Defined system instructions to control chatbot behavior
- Enforced response structure, tone, and safety requirements

### Query Processing

- User questions are validated before being sent to the model
- Blocked keywords are intercepted locally
- Safe requests are forwarded to the language model API

### Interactive Chat Interface

- Supports continuous user interaction through a terminal-based chatbot
- Allows users to ask multiple health-related questions during a session

## Sample Questions

- What causes a sore throat?
- How much water should I drink per day?
- What are the warning signs of a stroke?
- What is the difference between Type 1 and Type 2 diabetes?
- Why might someone experience chronic fatigue?

## Conclusion

This project demonstrates the development of a safety-focused AI health chatbot using modern large language models. By combining prompt engineering, content filtering, and responsible AI practices, the chatbot provides useful educational health information while maintaining user safety and encouraging professional medical consultation.

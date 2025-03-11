# AWS Lambda Chatbot with Gemini API Integration

A serverless chatbot built using AWS Lambda and the Gemini API. This project demonstrates how to create a conversational AI chatbot that processes user queries, maintains conversation memory, and responds dynamically using the Gemini AI model.

## Features

- **Serverless Architecture**: Built on AWS Lambda for scalable and cost-effective deployment.
- **Gemini API Integration**: Leverages the Gemini AI model for generating conversational responses.
- **Conversation Memory**: Maintains in-memory conversation history for each user (ephemeral in Lambda).
- **Error Handling**: Robust error handling for API calls and request processing.
- **Environment Variables**: Secure management of the Gemini API key using environment variables.

## Prerequisites

Before you begin, ensure you have the following:

1. **AWS Account**: To deploy and run the Lambda function.
2. **Gemini API Key**: Obtain an API key from [Gemini]([https://gemini.com](https://aistudio.google.com/apikey)).
3. **Python 3.x**: Installed on your local machine for development.
4. **AWS CLI**: Configured with your AWS credentials.

## How It Works
1. User Query: The user sends a query (e.g., "Hello, how are you?") to the Lambda function.
2. Gemini API Call: The Lambda function sends the query to the Gemini API for processing.
3. Conversation Memory: The chatbot maintains a simple in-memory conversation history for each user.
4. Response: The Gemini API generates a response, which is returned to the user.

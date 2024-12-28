# Chatbot with Gemini Flash and LangChain

This project demonstrates how to use LangChain with Google's Gemini Flash model to create a conversational assistant. The script leverages the Gemini model for generating responses and LangChain to simplify the integration of the AI model and prompt management.

## Requirements

Before running the script, ensure you have the following:

- Python 3.x
- Access to Google Cloud API with the Gemini API enabled.
- Necessary Python packages (`langchain` and `google-generativeai`).

## Setup and Installation

### Step 1: Install Dependencies

Install the required libraries by running the following commands:


### Step 2: Google API Key

You will need to obtain a Google API key for accessing the Google Gemini model. Follow these steps to get your API key:

1. Visit the [Google Cloud Console](https://console.cloud.google.com/).
2. Create a new project or select an existing one.
3. Go to **API & Services** > **Credentials**.
4. Generate a new API key.
5. Ensure the **Gemini API** is enabled for your project.

Once you have your API key, you will need to configure it in the script.

### Step 3: Running the Script

The script sets up the conversational AI assistant using LangChain and the Gemini Flash model. It configures the language model, defines a prompt template, and processes the user input to generate responses.

### Parameters:
- **Model**: Specifies the language model to use, such as `gemini-1.5-flash`.
- **Temperature**: Controls the creativity of the responses (values between 0.0 and 1.0).

### Step 4: Customizing the Prompt

The prompt template in the script can be modified to suit different types of inputs or response styles. You can adjust the template based on the desired behavior of the assistant.

## Troubleshooting

- **Invalid API Key**: If you encounter errors related to the API key, ensure that the API key is set correctly and that you have the necessary permissions to access the Gemini API.
- **Model Errors**: In case of errors or timeouts with the model, check your internet connection and ensure that the Gemini API is operational.
- **Dependency Issues**: Ensure you are using a compatible Python version and that the required dependencies are properly installed.
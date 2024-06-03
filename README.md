Gemini PDF Chatbot

This is a Streamlit application that allows users to upload PDFs and ask questions about the content. The application uses Langchain and Google Generative AI to process the PDFs and answer the user's questions in a conversational way.

Features

Upload multiple PDFs
Ask questions about the content of the PDFs
Get answers in a conversational format
Clear chat history
Requirements

Python 3.6 or later
Streamlit
Langchain
PyPDF2
Google Generative AI library
dotenv
Installation

Clone this repository.
Create a virtual environment and activate it.
Install the required libraries:
Bash
pip install streamlit langchain PyPDF2 genai dotenv
Use code with caution.
content_copy
Create a file named .env in the root directory of the project and add your Google API key:
GOOGLE_API_KEY=your_api_key
How to Use

Run the application:
Bash
streamlit run main.py
Use code with caution.
content_copy
Upload your PDFs in the sidebar.
Click the "Submit & Process" button.
Once processing is complete, ask your questions in the chat interface.
Example Usage

Imagine you have two PDFs, one about astronomy and one about history. You can upload both PDFs to the application and then ask questions like "What is the biggest star in the Milky Way?" or "What was the capital of ancient Rome?". The application will search the PDFs for the answer and provide you with a response.

Contributing

We welcome contributions to this project. Please see the CONTRIBUTING.md file for details.

License

This project is licensed under the MIT License. See the LICENSE file for details.

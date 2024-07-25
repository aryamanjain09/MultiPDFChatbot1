
# MultiPDF Chatbot

This python application is a generative AI chatbot which can learn from the PDFs you upload. You can ask questions about the PDFs using natural language, and the application will provide relevant responses based on the content of the documents. 




# Working
The application follows these steps to provide responses to your questions:

PDF Loading: The app reads multiple PDF documents and extracts their text content.

Text Chunking: The extracted text is divided into smaller chunks that can be processed effectively.

Language Model: The application utilizes a language model to generate vector representations (embeddings) of the text chunks.

Similarity Matching: When you ask a question, the app compares it with the text chunks and identifies the most semantically similar ones.

Response Generation: The selected chunks are passed to the language model, which generates a response based on the relevant content of the PDFs.


## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

`OPENAI_API_KEY`

`HUGGINGFACEHUB_API_TOKEN`


## Usage

Ensure that you have installed the required dependencies and added the API keys to the .env file.

Run the app.py file using the Streamlit CLI. Execute the following command:

`streamlit run app.py`

The application will launch in your default web browser, displaying the user interface.

Load PDF documents into the app by following the provided instructions.

Ask questions in natural language about the loaded PDFs using the chat interface.

## Screenshots

The application is able to interpret the 168-page FMS Casebook and provide information regarding its contents. It is also able to retain conversational history by understanding the context and providing the required frameworks asked in the 2nd prompt.

<img width="1440" alt="Chatbot" src="https://github.com/aryamanjain09/MultiPDFChatbot1/assets/115731877/587281cb-8b77-4c79-a819-9800548c3267">

<img width="806" alt="Chatbot2" src="https://github.com/aryamanjain09/MultiPDFChatbot1/assets/115731877/97460cf3-edf4-40c0-b22f-c0cf6a7f134d">


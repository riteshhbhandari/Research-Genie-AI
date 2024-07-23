Here's a README file for your project, "Research Genie AI":

# Research Genie AI

**Research Genie AI** is an advanced web application designed to interact with research papers using AI. It leverages AI to provide detailed answers to questions based on the contents of uploaded research papers. This project showcases the integration of AI technologies to enhance research efficiency and accessibility.

## Problem It Solves

Navigating through large volumes of research papers can be overwhelming and time-consuming. **Research Genie AI** simplifies this process by enabling users to:
- **Ask Questions**: Users can input questions related to the content of their research papers.
- **Get Detailed Answers**: The AI processes the research papers and provides comprehensive answers to the questions asked, improving the efficiency of literature reviews and information retrieval.

## Tech Stack

- **Python**: The primary programming language used for developing the application.
- **Streamlit**: Framework for building the web application interface.
- **PyPDF2**: Library for extracting text from PDF documents.
- **LangChain**: Framework for building AI-driven chains and processing.
- **Google Generative AI**: Utilized for embedding generation and conversational AI.
- **FAISS**: Vector search library for efficient similarity search.
- **Dotenv**: For managing environment variables.

## Libraries

- **streamlit**: To build the interactive web interface.
- **PyPDF2**: To read and extract text from PDF files.
- **langchain.text_splitter**: For splitting text into manageable chunks.
- **langchain_google_genai**: For generating embeddings and handling conversational AI with Google Generative AI.
- **langchain.vectorstores**: For managing vector stores and similarity searches.
- **langchain.chains.question_answering**: For creating QA chains using language models.
- **langchain.prompts**: For defining prompt templates.
- **dotenv**: For loading environment variables from a `.env` file.

## Features

- **PDF Upload**: Users can upload multiple PDF files containing research papers.
- **Text Chunking**: Extracted text is split into chunks for efficient processing.
- **Vector Embeddings**: Text chunks are converted into vector embeddings for semantic search.
- **Conversational AI**: Users can interact with the AI to ask questions about the content of the research papers.
- **Local Storage**: Vector embeddings are stored locally for quick retrieval.

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/research-genie-ai.git
    ```

2. Navigate to the project directory:

    ```bash
    cd research-genie-ai
    ```

3. Create a virtual environment and activate it:

    ```bash
    python -m venv venv
    source venv/bin/activate   # On Windows use `venv\Scripts\activate`
    ```

4. Install the required libraries:

    ```bash
    pip install -r requirements.txt
    ```

5. Set up environment variables:
    - Create a `.env` file in the project root directory.
    - Add your Google API key:

        ```
        GOOGLE_API_KEY=your_google_api_key_here
        ```

## Usage

1. Run the application:

    ```bash
    streamlit run app.py
    ```

2. Open your browser and navigate to `http://localhost:8501` to access the application.

3. Upload your research papers, and start asking questions to interact with the content.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request if you have suggestions or improvements.


Feel free to customize the README further based on any additional details or specific instructions relevant to your project.

## Screenshots 
<img width="1470" alt="Screenshot 2024-07-23 at 2 39 40 PM" src="https://github.com/user-attachments/assets/bcedf1a3-659c-4a6e-93da-bb7fd440b210">
<img width="1470" alt="Screenshot 2024-07-23 at 2 37 16 PM" src="https://github.com/user-attachments/assets/c67b60fc-ad01-41b1-9abe-06f0d1a5b42a">
<img width="336" alt="Screenshot 2024-07-23 at 2 39 52 PM" src="https://github.com/user-attachments/assets/58afb32e-e67d-408d-838c-4e03cc157be2">
<img width="1103" alt="Screenshot 2024-07-23 at 2 41 15 PM" src="https://github.com/user-attachments/assets/53e024de-e7a1-4b78-a9f4-5b3fa87e0791">

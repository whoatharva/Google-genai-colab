# Gemini-pro with Langchain 😎

This project demonstrates how to leverage **Gemini-pro** with **Langchain** for text generation, multimodal applications, and creating a Retrieval Augmented Generation (RAG) system to extract answers from PDFs. 
## Features

- Text Generation: Generate high-quality responses based on your queries using Gemini-pro.

- Multimodal Tasks: Handle text-based multimodal tasks using Langchain.
- RAG-based PDF Q&A: Extract answers from PDFs using a combination of Gemini and Chroma embeddings.
- PDF Processing: Load, split, and process PDFs to answer specific questions.
- Document Interaction: Query your documents using the Langchain retrieval-based approach.


## Installation

1. Clone the repository:

```bash
git clone https://github.com/whoatharva/Gemini-Project
cd Gemini-Project

```
2. Create a virtual environment and activate it:
```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
``` 
3. Install the required packages:
```bash
pip install -r requirements.txt
```
4.Set up environment variables:
- Create a .env file in the root of your project and add your Google API key:
```bash
GOOGLE_API_KEY=your-google-api-key
```
## Tech Stack

- **Python**: Programming language used.
- **Google Generative AI**: For text generation and embeddings.
- **Langchain**: For constructing chains and document processing.
- **ChromaDB**: For building vector indexes and retrieving document embeddings.
- **pypdf**: For loading and processing PDFs.

## Environment Variables

To run this project, you will need to add the following environment variables to your .env file


```bash
GOOGLE_API_KEY="YOUR_API_KEY_HERE"

```


## Feedback

Contributions are welcome! Feel free to submit pull requests or open issues for suggestions or improvements.
